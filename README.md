# Obter Dados de Dispositivos IoT

## Descrição do Projeto
Este projeto foi desenvolvido para coletar, processar e visualizar dados provenientes de dispositivos IoT. Utiliza requisições HTTP para acessar uma API que fornece dados de sensores, como luminosidade, permitindo análise e monitoramento desses dados.

## Funcionalidades
- **Coleta de Dados**: Obtém informações de sensores IoT via API.
- **Processamento**: Trata os dados recebidos para posterior análise.
- **Visualização**: Utiliza bibliotecas de Python para gerar gráficos representativos dos dados coletados.

## Tecnologias Utilizadas
- **Python 3**
- **Requests**: Para fazer requisições HTTP e obter os dados da API.
- **Matplotlib**: Para gerar gráficos baseados nos dados coletados.
- **NumPy**: Para manipulação e tratamento de dados numéricos.

## Como Executar o Projeto
1. Instale as dependências necessárias:
   ```bash
   pip install requests matplotlib numpy
   ```
2. Execute o notebook no Jupyter Notebook ou Jupyter Lab:
   ```bash
   jupyter notebook ObterDadosPython.ipynb
   ```
3. Siga as instruções do notebook para realizar a coleta e análise dos dados.

## Melhorias Futuras
- Implementar armazenamento dos dados em banco de dados.
- Criar dashboard interativo para exibição dos resultados.
- Adicionar suporte para múltiplos tipos de sensores.

---
Projeto focado na coleta e análise de dados IoT.

