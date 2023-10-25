# Google Maps Scraper

This is simple scraper that uses Playwright to extract data from Google Maps. 

This example is made for educational purposese.

This scrapit is easy to customize.

check both Excel & CSV files (google_maps_data) to see how final data will look like. 

## To Install:
- `pip install -r requirements.txt`
- `pip install pytest-playwright`
- `pip install pytest-playwright playwright -U`
- `python -m playwright install chromium`
- `se aparecer erro digite o comando acima e depois --user`

## to Run:
- `python main.py -s="onde você quer mais o que você precisa" -t=quantos`
- `ex: python main.py -s="são paulo lojas de roupa" -t=100`

# Obs:
- `O arquivo gerado csv e xlsx são padrões, então após gerar a lista crie uma cópia do arquivo e cole em outro lugar para não perder. EM HIPÓTESE ALGUMA ALTERE O LOCAL OU O NOME DOS ARQUIVOS google_maps_data.csv e google_maps_data.xlsx`
