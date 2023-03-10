# sistema_de_risco
Sistema de risco do cliente
Criando uma Aplicação WEB com a Máquina Preditiva
Deploy - Implementando a Maquina Preditiva na WEB
Passo a Passo Implementação do Sistema de Classificação de Risco do Cliente:
1° Realizar o download da ferramenta "Visual Studio Code" no link abaixo:

https://code.visualstudio.com/

2° Instalar a ferramenta: Clicar em "next" e "finish" (simples assim...)

3° Criar um diretório "app" no seu Drive "C"

Ex: C:\app

4° Fazer o Download dos arquivo no github

5° Salvar essa pasta dentro do diretório app.

Ex: C:\app\sistema classificacao

Obs: temos 3 arquivos:

1° risco.csv - Nossa fonte de dados

2° app_risco.py - Nosso Aplicativo web

3° Sistema_Classificação_Risco.ipynb - Nosso Script de Criação da Máquina Preditiva

6° Abrir o VS Code e clicar no menu "File", depois "Open Folder" e vai navegar até o diretório "C:\app\sistema classificacao"

7° Vai no menu "terminal", depois "New Terminal". Perceba que vai abrir, lá embaixo, um terminal de comando, tipo o "CMD" (tela preta) do windows.

8° executar os seguinte comandos:

a) pip install plotly + tecla enter

b) pip install streamlit + tecla enter

9° Instalar o Anaconda

https://www.anaconda.com/products/individual

10° Executar o comando de abertura (no terminal do VS Code)

streamlit run app_risco.py

obs: Nosso sistema vai abrir na WEB. Ver no seu navegador web.
