[![GitHub](https://img.shields.io/github/license/jdeveloperanalyst/Analise-de-Dados)](https://github.com/jdeveloperanalyst/Analise-de-Dados/blob/master/LICENSE)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-05122A?style=flat&logo=linkedin)](https://www.linkedin.com/in/jonatas-silva-dev-6a6f6e/)

# Automação de Processos

No dia a dia das empresas, é muito comum que existam operações manuais que além de extremamente repetitivas são suscetíveis a erro visto que são feitas manualmente. O objetivo deste projeto foi criar um código com o qual você possa resolver este problema fazendo uma automação com integração web utilizando a linguagem de programação Python.

## Sobre o Projeto

Para este projeto foi utilizado uma base de dados que basicamente é um <kbd>arquivo Excel</kbd> onde contém alguns produtos e valores criados. Dentre esses valores criados, existe a cotação de algumas moedas... como: O <kbd>dólar</kbd>, o <kbd>euro</kbd> e o <kbd>ouro</kbd> no qual contém valores predefinidos. Sendo assim, utilizando os recursos que o Python nos fornece, este código será responsável em buscar na internet as cotações atuais de cada moeda e atualizar na nossa base de dados, fazendo com que seja possível além de atualizar as cotações, calcular também o <kbd>preço de compra</kbd> e o <kbd>preço de venda</kbd> com base na margem de lucro de cada produto. Logo em seguida armazenar esses valores atualizados em um novo arquivo Excel, no qual será possível ter uma nova base de dados atualizada. Tudo isso de forma totalmente automática.

## Selenium

O <kbd>Selenium</kbd> é uma biblioteca muito utilizada como interface com o navegador. Ela funciona como um robô que clica, insere dados, etc... em páginas web, interagindo com os sites como se fosse você. Muito útil para processos repetitivos como este que temos aqui. E Antes de mostrar a estrutura do código vale <kbd>destacar</kbd> uma atualização importante sobre a biblioteca no qual altera o seu uso no que se refere a interação com os navegadores. <kbd>Confira abaixo</kbd> uma breve explicação sobre este update:


https://user-images.githubusercontent.com/112918533/202278285-37f227fa-62a8-40f7-87c6-2ca0866d7b3f.mp4


## Estrutura do código

Mostrando um pouco a estrutura do código, irei falar sobre as bibliotecas utilizadas e cada etapa do processo até a criação de um novo arquivo com os dados atualizados. <kbd>Confira abaixo:</kbd> 


https://user-images.githubusercontent.com/112918533/202279552-c0783ce8-0cac-4ccd-8266-b99b3a380c40.mp4


***
> "O Sucesso começa com um sonho, do sonho para a meta, da meta para a disciplina, da disciplina para a persistência e da persistência para a conquista"
