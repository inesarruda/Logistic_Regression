# Logistic_Regression
Machine Learning Project using Logistic regression to predict whether or not a user has clicked on an online ad

# Projeto Regressão Logística - Machine Learning

Nesse projeto vamos trabalhar com um conjunto de dados fictício, que indica se um usuário clicou ou não em um anúncio online. A partir disso, vamos criar um modelo para prever se o usuário, baseado em suas características, vai clicar ou não no anúncio. O modelo de machine learning que será utilizado será uma regressão lgística

O dataset contém as seguintes features:

* **'Daily Time Spent on Site':** tempo do consumidor no site em minutos
* **'Age':** Idade do cliente em anos
* **'Area Income':** Renda média da área geográfica do consumidor
* **'Daily Internet Usage':** Média de minutos que o consumidor gasta na internet
* **'Ad Topic Line':** Título do anúncio
* **'City':** Cidade do consumidor
* **'Male':** Se o consumidor era um Homem 
* **'Country':** País do consumidor
* **'Timestamp':** Hora em que o consumidor clicou no anúncio ou em fechar a janela
* **'Clicked on Ad':** 0 or 1 indicando se o consumidor clicou no anúncio

<img  src = "!https://github.com/inesarruda/Logistic_Regression/assets/112672449/ef299604-31b6-4ed5-bde8-05355363df0f" width= "401px"/>
![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/5c5189bf-1e29-48b3-9a54-ec75b0f9219e)


## Vamos fazer mais algumas análises estatísticas, para isso vamos olhar um mapa de calor com as correlações entre as features, e vamos demonstrar algumas delas através de gráficos

<div align="center">
<img src="![baixados](https://github.com/inesarruda/Logistic_Regression/assets/112672449/4e7df0a7-bdcf-466a-a2c7-3f8df9a2dce4)" width="400px" />
</div>

### Vimos também que idade e uso de internet tem uma correlação negativa, ou seja, quanto menor a idade mais internet se usa diariamente e vice-versa.

<img  src = "![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/ab15d2ed-5033-4088-9726-5b7315ed6294)" width= "401px"/>

### Vemos que o gráfico acima realmente apresenta dois "nichos". No lado esquedo superior temos o grupo de menor idade e com maior uso de internet, enquanto no lado direito inferior temos maior idade e menor uso de internet. 

### Vimos que há uma alta correlação entre idade e clicar nos anúncios. Vamos então separar as idades em faixas e verficar o comportamento. 

### Para separar de em faixas de idade, vamos utilizar o comando cut

<img  src = "![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/f3bb70a0-fe65-4028-bbcf-08a3680c2f40)" width= "401px"/>

### Nota-se que quanto maior a idade, maior a tendência em clicar nos anúncios da página.

### Essa análise é importante para entender a melhor estratégia de propaganda de acordo com o público.

# Regressão Logística

**Vamos começar divivindo o dataset nos dados de treino e teste.**
**Também vamos definir as features e o target que serão utilizados**
<img  src = "![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/d8edda3b-e1dc-4256-be6f-1525bbcfbb89)" width= "401px"/>

### Colocando as métricas em uma Matriz de Confusão
<img  src = "![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/60d8e68b-2f58-4c0c-97bf-6c1698a65595)" width= "401px"/>






