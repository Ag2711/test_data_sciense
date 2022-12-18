# test_data_sciense
Подскажите пожалуйста, почему не вычисляется среднее усредненное
from scipy import stats
import pandas as pd
state = pd.read_excel('C:\\Users\\Антон\\Desktop\\state.xlsx')
state['Население'].mean()
stats.trim_mean(state['Население'], 0.1)
state['Население'].median()
print(stats.trim_mean(state['Население'], 0.1), state['Население'].mean(),state['Население'].median())
