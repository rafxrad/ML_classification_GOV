# ML_classification_GOV

Este documento orienta a utilização do Google Colab para rodar o modelo de aprendizado de máquina desenvolvido neste trabalho.

## Requisitos
Antes de iniciar, verifique se você possui:
- Uma conta no Google.
- Acesso ao Google Drive.
- Conhecimento básico em Python e bibliotecas de Machine Learning.

##  Passos para Execução no Google Colab

###  Acessar o Google Colab
- Acesse [Google Colab](https://colab.research.google.com/).
- Faça login com sua conta do Google.
- Crie um novo notebook ou carregue o arquivo do projeto (Model_Evaluation_Training_Random_Forest.ipynb).

### Montar o Google Drive
Para acessar os dados armazenados no Google Drive, execute:
```python
from google.colab import drive
drive.mount('/content/drive')
```
Isso permitirá o acesso aos arquivos do seu Drive dentro do notebook.

### Instalar Dependências
Instale as bibliotecas necessárias com:
```python
!pip install -q pandas numpy scikit-learn matplotlib seaborn
```



### Carregar os Dados
Carregue os dados diretamente do Google Drive:
```python
import pandas as pd

# Ajuste o caminho para onde você colocou o arquivo do dataset no seu drive
data = pd.read_csv('/content/drive/MyDrive/dataset_tcc.csv')
```



