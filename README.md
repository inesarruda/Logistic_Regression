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

 ![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/1de40ed1-4091-4f6e-ad85-4397ff09c773)


## Vamos fazer mais algumas análises estatísticas, para isso vamos olhar um mapa de calor com as correlações entre as features, e vamos demonstrar algumas delas através de gráficos

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/3af566c8-4593-400c-b989-f54d6cb4100b)

### Vimos também que idade e uso de internet tem uma correlação negativa, ou seja, quanto menor a idade mais internet se usa diariamente e vice-versa.

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/22ea79db-278e-4805-a957-6e74323323dd)

### Vemos que o gráfico acima realmente apresenta dois "nichos". No lado esquedo superior temos o grupo de menor idade e com maior uso de internet, enquanto no lado direito inferior temos maior idade e menor uso de internet. 

### Vimos que há uma alta correlação entre idade e clicar nos anúncios. Vamos então separar as idades em faixas e verficar o comportamento. 

### Para separar de em faixas de idade, vamos utilizar o comando cut

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/eb4ecdbd-2ae5-4e4b-913e-4aff2ebe6aa5)


### Nota-se que quanto maior a idade, maior a tendência em clicar nos anúncios da página.

### Essa análise é importante para entender a melhor estratégia de propaganda de acordo com o público.

# Regressão Logística

**Vamos começar divivindo o dataset nos dados de treino e teste.**
**Também vamos definir as features e o target que serão utilizados**

![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/0af73b99-4c29-49a3-a8ec-7656b699b03d)

### Colocando as métricas em uma Matriz de Confusão
![image](https://github.com/inesarruda/Logistic_Regression/assets/112672449/9d154375-3722-474d-8b83-97e2d02176f9)


## A análise completa está disponível no notebook "Projeto Regressão Logística - Inês.ipynb" deste repositório






