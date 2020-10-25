
<h1 align="center">Bem-vindo ao Finding Donors for CharityML 👋</h1>
<p>
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg" />
  </a>
</p>

> Esse repositório possui um algoritmo de aprendizado supervisionado com o objetivo de reduzir o número de cartões que são enviadas pedindo doação para caridade

## Requerimentos

- [x] [Python3](https://www.python.org/downloads/) (recomendamos usar o [Anaconda](https://www.anaconda.com/))
- [x] [Jupyter Notebook](https://jupyter.org/)
- [x] [scikit-learn](http://scikit-learn.org/stable/)
- [x] [Numpy](https://numpy.org/)
- [x] [Matplotlib](https://matplotlib.org/)
- [x] [Pandas](https://pandas.pydata.org/)

## Instruções de Uso

1. Clone o repositório
```sh
git clone https://github.com/zerocoolbr/Finding-Donors-for-CharityML.git
```

Entrar na pasta `Finding-Donors-for-CharityML` e executar o comando

```sh
jupyter notebook finding_donors.ipynb
```

Dentro do do Notebook estará todas as instruções de uso.

## Dados

O dataset contém aproximadamente 32000 amostras, onde cada um possui 13 features. Esse dataset é uma versão modificada da publicada no artigo _"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid"_ por Ron Kohavi. Você pode encontrar esse artigo [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), com o dataset original hospedado na [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Features**

-   `age`: Age
-   `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
-   `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
-   `education-num`: Number of educational years completed
-   `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
-   `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
-   `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
-   `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
-   `sex`: Sex (Female, Male)
-   `capital-gain`: Monetary Capital Gains
-   `capital-loss`: Monetary Capital Losses
-   `hours-per-week`: Average Hours Per Week Worked
-   `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**

-   `income`: Income Class (<=50K, >50K)

## Autor

👤 **Marcos Santana**

- Github: [@zerocoolbr](https://github.com/zerocoolbr)
- LinkedIn: [@marcosbrs](https://linkedin.com/in/marcosbrs)

## 📝 License

Copyright © 2020 [Marcos Santana](https://github.com/zerocoolbr).<br />
This project is [MIT](LICENSE) licensed.
