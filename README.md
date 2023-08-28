# Machine Learning Project - Logistic Regression

Machine Learning Project using Logistic regression to predict whether or not a user has clicked on an online ad

# Projeto Regressão Logística - Machine Learning

Nesse projeto vamos trabalhar com um conjunto de dados fictício, que indica se um usuário clicou ou não em um anúncio online. A partir disso, vamos criar um modelo para prever se o usuário, baseado em suas características, vai clicar ou não no anúncio. O modelo de machine learning que será utilizado será uma regressão logística.

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

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/9d627311-7ae4-477c-8e54-393a92ab905c)

## Vamos fazer mais algumas análises estatísticas, para isso vamos olhar um mapa de calor com as correlações entre as features, e vamos demonstrar algumas delas através de gráficos

<div align="center">
<img src="![baixados](https://github.com/inesarruda/Logistic_Regression/assets/112672449/4e7df0a7-bdcf-466a-a2c7-3f8df9a2dce4)" width="400px" />
</div>

![baixados](https://github.com/inesarruda/Logistic_Regression/assets/112672449/4e7df0a7-bdcf-466a-a2c7-3f8df9a2dce4) 

### Vimos também que idade e uso de internet tem uma correlação negativa, ou seja, quanto menor a idade mais internet se usa diariamente e vice-versa.

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/2e515634-7d78-40c2-8d0f-f1b337e074c3)


### Vemos que o gráfico acima realmente apresenta dois "nichos". No lado esquedo superior temos o grupo de menor idade e com maior uso de internet, enquanto no lado direito inferior temos maior idade e menor uso de internet. 

### Vimos que há uma alta correlação entre idade e clicar nos anúncios. Vamos então separar as idades em faixas e verficar o comportamento. 

### Para separar de em faixas de idade, vamos utilizar o comando cut

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/cae01576-0efa-4598-8ebb-023d157ef060)

### Nota-se que quanto maior a idade, maior a tendência em clicar nos anúncios da página.

### Essa análise é importante para entender a melhor estratégia de propaganda de acordo com o público.

# Regressão Logística

**Vamos começar divivindo o dataset nos dados de treino e teste.**
**Também vamos definir as features e o target que serão utilizados**

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/4872fc19-a68a-4b14-983f-52f48e19a391)


### Colocando as métricas em uma Matriz de Confusão
![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/a7440b29-5dfd-45d9-9329-a90d8b6f0035)

## A análise completa está disponível no notebook "Projeto Regressão Logística - Inês.ipynb" deste repositório






