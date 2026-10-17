# Guardar como .github/workflows/snake.yml en el repo ErwinGonzalezBonilla/ErwinGonzalezBonilla
name: Generar serpiente de contribuciones

on:
  schedule:
    - cron: "0 */12 * * *"   # cada 12 horas
  workflow_dispatch:          # permite lanzarlo a mano
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generar SVG
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark&color_snake=#7CB8FF&color_dots=#0D1B2E,#1E4D8C,#3A6FB8,#5B93D9,#7CB8FF

      - name: Publicar en la rama output
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

