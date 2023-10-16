## Contoh sintaks untuk pemanggilan data tersebut

url = 'https://github.com/Riskyrianda/Data_analyst/blob/main/Database_CSV/AB_NYC_2019.xlsx%20-%20AB_NYC_2019.csv?raw=true'
df= pd.read_csv(url,index_col=0)
df.head(10)
