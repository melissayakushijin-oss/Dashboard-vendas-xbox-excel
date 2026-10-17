# 🎮 Dashboard de Vendas do Xbox Game Pass com Excel

Projeto desenvolvido no desafio **"Criando um Dashboard de Vendas do Xbox com Excel"** da [DIO](https://www.dio.me/).

O objetivo foi transformar uma base bruta de assinaturas do **Xbox Game Pass** em um dashboard visual e interativo, que responde perguntas de negócio e apoia a tomada de decisões baseada em dados.

## 🖼️ Prévia

![Dashboard Xbox Game Pass](dashboard.png)

## 📁 Arquivos do repositório

| Arquivo | Descrição |
|---|---|
| `DASHBOARD VENDAS.xlsx` | Pasta de trabalho completa: base de dados, cálculos e dashboard |
| `dashboard.png` | Captura de tela do dashboard |

## 🛠️ Sobre o projeto

- Organização do projeto seguindo o **Método ABCDE**
- Estruturação da base em formato de **tabela** (Data View)
- **Tabelas dinâmicas** para responder às perguntas de negócio
- **Gráfico dinâmico** de faturamento por renovação automática
- **Segmentação de dados** por tipo de assinatura, conectada a todas as tabelas dinâmicas, que filtra o painel inteiro
- **Big Numbers** do EA Play Season Pass e do Minecraft Season Pass, ligados às tabelas dinâmicas com `INFODADOSTABELADINÂMICA` (`GETPIVOTDATA`)
- **Info Context** com o período de cálculo e a data de atualização
- **Estilização** com a identidade visual do Xbox: paleta de verdes, logos, ícones e menu lateral

### Perguntas de negócio

1. Qual o faturamento total de vendas das assinaturas?
2. Qual o faturamento separado por assinaturas com e sem renovação automática?
3. Qual o total de vendas do EA Play Season Pass?
4. Qual o total de vendas do Minecraft Season Pass?

### Estrutura da planilha

| Aba | Conteúdo |
|---|---|
| **Assets** | Paleta de cores, logos e ícones usados no dashboard |
| **Bases** | Base de dados formatada como tabela |
| **Cálculos** | Tabelas dinâmicas que respondem às perguntas de negócio |
| **Dashboard** | Painel final com Big Numbers, gráfico e segmentação de dados |

## 📊 Dados utilizados

A base, fornecida pela DIO, contém **295 assinaturas** do Xbox Game Pass iniciadas em **2024**, com as colunas:

`Subscriber ID` · `Name` · `Plan` (Core, Standard, Ultimate) · `Start Date` · `Auto Renewal` · `Subscription Price` · `Subscription Type` (Monthly, Quarterly, Annual) · `EA Play Season Pass` · `EA Play Season Pass Price` · `Minecraft Season Pass` · `Minecraft Season Pass Price` · `Coupon Value` · `Total Value`

## ▶️ Instruções para reprodução

1. Baixe o arquivo `DASHBOARD VENDAS.xlsx` deste repositório (botão **Download raw file**).
2. Abra no **Microsoft Excel 2016 ou superior**. A segmentação de dados não funciona no Google Sheets nem no LibreOffice.
3. Na aba **Dashboard**, use a segmentação **Subscription Type** para alternar entre Monthly, Quarterly e Annual.
4. Para usar novos dados, adicione as linhas na tabela da aba **Bases** e clique em **Dados → Atualizar Tudo**.

## 👩‍💻 Autora

**Melissa Yakushijin**: [GitHub](https://github.com/melissayakushijin-oss)
