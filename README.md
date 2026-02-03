# 📊 Projeto de Estudo: Análise de Dados do Censo 2022

![Status](https://img.shields.io/badge/Status-Em_Andamento-e16b16?style=for-the-badge)

## 📝 Sobre o Projeto

Este projeto guarda meus estudos práticos em **Análise de Dados**. O objetivo principal foi pegar dados reais e brutos do Censo 2022 (IBGE) e transformá-los em informações visuais úteis, usando a linguagem Python.

Simulei o trabalho real de um analista: comecei lendo arquivos bagunçados, organizei as informações, fiz os cálculos necessários e terminei criando gráficos para visualizar os resultados.

> **Nota:** Se você quiser entender a lógica por trás de cada linha de código, eu deixei tudo explicado passo a passo dentro do arquivo principal (`analise_censo_2022.ipynb`).

## 🎯 O que eu pratiquei neste projeto

Este projeto serviu para treinar as seguintes habilidades:

* **Coleta e Preparação:** Como ler arquivos de diferentes formatos (Excel e CSV) e prepará-los para uso.
* **Limpeza de Dados:** Como arrumar tabelas, corrigir nomes de colunas e ajustar tipos de números e textos.
* **Cruzamento de Informações:** Como juntar duas tabelas diferentes (uma com estatísticas e outra com nomes de cidades) para criar uma análise mais completa.
* **Análise Exploratória:** Como filtrar apenas o que interessa, agrupar dados por Estado (UF) e fazer somas e cálculos automáticos.
* **Visualização:** Como criar gráficos de barras (verticais e horizontais) para apresentar as descobertas de forma clara.

## 🗂️ Organização das Pastas

* `dados/`: Onde estão os arquivos originais que baixei (o Censo e a lista de Municípios).
* `notebook/analise_censo_2022.ipynb`: O arquivo principal com todo o código e minhas anotações explicando o processo.
* `saida/`: Onde ficam os arquivos finais que o código gerou (ex: a planilha com o ranking dos 5 estados).

## 🚀 Ferramentas Utilizadas

* **Python:** A linguagem de programação usada.
* **Pandas:** A biblioteca que usei para carregar e mexer nas tabelas de dados (é como um Excel superpotente dentro do código).
* **Matplotlib:** A ferramenta usada para desenhar os gráficos finais.

## ⚙️ Como rodar o projeto no seu computador

1.  Baixe ou clone este repositório:
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repo.git](https://github.com/seu-usuario/nome-do-repo.git)
    ```
2.  Instale as bibliotecas necessárias para o código funcionar:
    ```bash
    pip install pandas matplotlib openpyxl
    ```
3.  Abra o arquivo `.ipynb` no seu editor de código preferido (como VS Code ou Jupyter Lab).

---
*Desenvolvido como parte do meu portfólio de estudos em Análise de Dados.*