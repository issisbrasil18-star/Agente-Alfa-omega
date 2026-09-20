# Agente Alfa Omega

Bot/agente de criptomoedas com dashboard web, em **Python + Flask**.

Cópia pública do projeto **Agente Zeus**
(https://github.com/issisbrasil18-star/Agente-Zeus) — mesmo código,
repositório aberto para qualquer pessoa ver e usar.

## Como rodar

```bash
cd dashboard
pip install -r requirements.txt
python app.py
```

Depois abra http://localhost:5000

## Funcionalidades

- Preços ao vivo das top 20 moedas (CoinGecko), variação 24h e 7d
- Carteira com valor total e variação por posição
- Alertas de preço e de variação 24h
- Análise do agente: sentimento do mercado, destaques e leitura da carteira
- Histórico de preços em SQLite

## Estrutura

```
/
├── README.md            # este arquivo
├── .gitignore
└── dashboard/           # app Flask (bot de crypto)
    ├── app.py
    ├── requirements.txt
    ├── README.md
    ├── static/css/
    └── templates/
```
