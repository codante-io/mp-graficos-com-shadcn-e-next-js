# Gráficos com Shadcn e Next.js

Muitas vezes a melhor forma de "exibir" dados é através de gráficos. E para grande parte dos casos não é necessário que sejamos "experts" em *data science* - basta apenas que a gente conheça as ferramentas certas para essa tarefa. E é exatamente isso que se tornaram algumas bibliotecas de gráficos para React - uma forma simples e rápida de construirmos gráficos dinâmicos e bonitos.  

Neste Mini Projeto vamos criar uma visualização com gráficos sobre os gastos dos senadores brasileiros.

## 🤓 Antes de começar

Esse Mini Projeto não possui um template pronto. Isso significa que você deverá começar, do zero, seu projeto Next.js. Entretanto, os dados que alimentarão os gráficos deverão vir da API de Gastos de Senadores, que nós do Codante criamos e preparamos. 

A documentação da API está em [neste link](https://docs.apis.codante.io/gastos-senadores). 

Também vale a pena contextualizar o que são os dados com os quais estamos trabalhando: trata-se das despesas com Cotas para Exercício da Atividade Parlamentar dos Senadores (CEAPS), que basicamente são "reembolsos" de despesas gerais com gabinete e atividade parlamentar. Alguns exemplos incluem assessoria parlamentar (contratação de pessoal para auxiliar em atividades como elaboração de projetos de lei e atendimento à população), material de expediente (compra de materiais de escritório, como papel e computadores), locação de imóveis (aluguel de espaços para escritórios), serviços de comunicação (contratação de internet e telefone), viagens e diárias (despesas com viagens para eventos relacionados ao mandato), e outras despesas (como eventos e divulgação de atividades parlamentares).

## 🔨 Requisitos

- Crie o Gráfico de Gastos por UF
	- Crie uma visualização de gráfico de barras horizontal
	- Cada barra do gráfico deverá corresponder a um estado brasileiro (UF) 
	- Adicione no gráfico a média de gastos de todas as UFs
		- Você deverá calcular esses valores e adicionar aos dados originais da API
		- A barra que representa a média deverá estar destacada com outra cor no gráfico
	- Transforme os dados conforme o necessário - a transformação e saneamento dos dados também fazem parte do Mini Projeto!
	- Adicione tooltips e labels para deixar o gráfico mais legível

- Crie o Gráfico de Gastos por Partido
	- Crie uma visualização de gráfico de barras horizontal
	- Cada barra do gráfico deverá corresponder a um estado brasileiro (UF) 
	- Adicione no gráfico a média de gastos de todas as UFs
		- Você deverá calcular esses valores e adicionar aos dados originais da API
		- A barra que representa a média deverá estar destacada com outra cor no gráfico
	- Transforme os dados conforme o necessário - a transformação e saneamento dos dados também fazem parte do Mini Projeto!
	- Adicione tooltips e labels para deixar o gráfico mais legível

- Crie botões dinâmicos que irão trocar as visualizações entre os dois gráficos (UF e Partido)
- Crie um seletor que irá trocar o ano dos dados - desde 2020 até 2024
- Você deverá utilizar a biblioteca *shadcn/charts* para construir seus gráficos


> 👀 **Dicas:**
> - Dica A sobre Req 2.
> - Dica B sobre Req 2.


## 🔨 Desafio extra para quem quer ir além

Se você quiser mergulhar ainda mais nos dados, dá uma olhada na [documentação](https://docs.apis.codante.io/gastos-senadores) da nossa API. Uma possível - e interessante - implementação de gráficos nestes dados é a criação de um gráfico de pizza que demonstra a divisão das categorias/tipos de despesas.

## 🎨 Design Sugerido

Temos uma sugestão de design no Figma. Entretanto, fique à vontade para montar a aplicação conforme a sua criatividade.

### Figma

🔗 [Link do design](https://www.figma.com/community/file/1415654074409973077/mini-projeto-graficos-com-shadcn-charts-e-next-js)

## 👉🏽 O que você irá praticar:

### Next.js

- Criação de um novo projeto
- Fetch de dados de API externa usando server components

### shadcn/charts

- Criação de gráficos com a biblioteca

### Pré requisitos

- Conhecimento básico de Next.js e server components
- Conhecimento de React
