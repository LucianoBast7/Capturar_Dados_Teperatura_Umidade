# Captura de Dados do Clima

Este projeto em Python utiliza a API do OpenWeatherMap para capturar dados de temperatura e umidade da cidade de São Paulo. A aplicação possui uma interface gráfica desenvolvida com Tkinter, permitindo ao usuário coletar dados de forma simples e prática.

## Funcionalidades

- **Requisição à API**: Coleta dados climáticos em tempo real.
- **Extração de Dados**: Obtém temperatura, umidade e data/hora da captura.
- **Classificação da Umidade**: Classifica a umidade como "Alta", "Normal" ou "Baixa".
- **Armazenamento em Excel**: Salva os dados coletados em um arquivo Excel (`historico_clima.xlsx`).
- **Feedback Visual**: Informa ao usuário sobre o sucesso ou falha na captura dos dados.

## Tecnologias Utilizadas

- Python
- Tkinter (para interface gráfica)
- Requests (para requisições HTTP)
- OpenPyXL (para manipulação de arquivos Excel)
- OpenWeatherMap API (para obter dados climáticos)

## Como Usar

# Configuração da API

Insira sua chave de API no código:

```python
api_key = "sua_chave_api_aqui"
```

Você pode obter uma chave de API gratuita neste link: https://openweathermap.org/.

# Execute o Programa:
Execute o script Python. A interface gráfica aparecerá.
Clique no botão (`Capturar Dados de Clima`) para iniciar a coleta de dados.

# Verifique o Arquivo Excel
Os dados coletados serão salvos em um arquivo chamado (`historico_clima.xlsx`) na mesma pasta do script.
