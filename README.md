from google.colab import files
uploaded = files.upload()
df = pd.read_csv('train.csv')
df.head()
