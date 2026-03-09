# 🔥 Sistema de Alerta Precoce de Queimadas na Amazônia Legal

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Folium](https://img.shields.io/badge/Folium-Maps-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📋 Sobre o Projeto

Este projeto desenvolveu um **Sistema de Alerta Precoce de Queimadas** para a Amazônia Legal, utilizando dados do INPE e técnicas de Machine Learning. O objetivo é auxiliar o IBAMA e órgãos ambientais na alocação preventiva de recursos e combate a incêndios florestais.

## 🎯 Problema de Negócio

Queimadas ilegais na Amazônia causam danos ambientais, econômicos e de saúde pública. O IBAMA precisa de ferramentas para:
- Antecipar focos de calor
- Alocar brigadas de incêndio preventivamente
- Entender padrões sazonais e regionais

## 📊 Principais Descobertas

| Categoria | Resultado |
|-----------|-----------|
| **Estados críticos** | MT (25.2%) e PA (20.5%) concentram 45% dos focos |
| **Bioma mais afetado** | Amazônia com 65.4% dos focos |
| **Mês de pico** | Janeiro (simulado - ajustar com dados reais) |

## 🤖 Modelagem Preditiva

- **Algoritmos testados:** Random Forest e Gradient Boosting
- **Melhor modelo:** Random Forest
- **MAE (erro médio):** 0.1323
- **Variáveis mais importantes:**
  - Umidade: 24.8%
  - Temperatura: 24.0%
  - Precipitação: 23.8%

## 🗺️ Visualizações

O projeto inclui um **mapa interativo** com:
- Camada de calor com 10.000 focos
- Clusters coloridos por bioma (Amazônia, Cerrado, Pantanal)
- Popups com informações detalhadas

## 📁 Arquivos do Projeto

- `estatisticas_estado.csv` - Dados agregados por estado
- `feature_importance.csv` - Importância das variáveis no modelo
- `amostra_dados.csv` - Amostra de 1000 registros
- `notebook_completo.ipynb` - Código completo da análise

## 🚀 Como Executar

1. Clone este repositório
2. Abra o notebook no Google Colab
3. Execute as células sequencialmente

## 🔮 Próximos Passos (Versão 2.0)

- [ ] Integrar API oficial do INPE
- [ ] Adicionar dados de desmatamento (PRODES)
- [ ] Implementar alertas automáticos
- [ ] Deploy no Streamlit Cloud

## 📝 Licença

MIT

## 👨‍💻 Autor

Rafael Samogim Pereira - [LinkedIn]([https://linkedin.com/in/seu-perfil](https://br.linkedin.com/in/rafael-samogim-pereira-973b7a293)) - [GitHub](https://github.com/rsamogim)
