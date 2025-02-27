# ML_classification_GOV

# Uso do Google Colab para Classificação de Informações Sigilosas

Este documento orienta a utilização do Google Colab para rodar o modelo de aprendizado de máquina desenvolvido neste trabalho.

## 📌 Requisitos
Antes de iniciar, verifique se você possui:
- Uma conta no Google.
- Acesso ao Google Drive.
- Conhecimento básico em Python e bibliotecas de Machine Learning.

## 🚀 Passos para Execução no Google Colab

### 1️⃣ Acessar o Google Colab
- Acesse [Google Colab](https://colab.research.google.com/).
- Faça login com sua conta do Google.
- Crie um novo notebook ou carregue o arquivo do projeto.

### 2️⃣ Montar o Google Drive
Para acessar os dados armazenados no Google Drive, execute:
```python
from google.colab import drive
drive.mount('/content/drive')
```
Isso permitirá o acesso aos arquivos do seu Drive dentro do notebook.

### 3️⃣ Instalar Dependências
Instale as bibliotecas necessárias com:
```python
!pip install -q pandas numpy scikit-learn matplotlib seaborn
```

```

### 4️⃣ Carregar os Dados
Carregue os dados diretamente do Google Drive:
```python
import pandas as pd

file_path = '/content/drive/MyDrive/dataset_.csv'  # Ajuste o caminho para onde você colocou o arquivo do dataset no seu drive
 df = pd.read_csv(file_path)
df.head()
```



