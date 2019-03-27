# ESTUDO_MANUTENCAO_FOG
#Este trabalho visa analisar a quantidade de horas paradas para realização de manutenção preventiva e corretiva para estabelecer e ou validar o percentual de parada para manutenção do setor. 

#importar bibliotecas
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

#Leitura do arquivo
manutencao = pd.read_csv('DADOS2.csv', 'r')

print('Este dataset possui % linhas e % colunas' % (manutencao.shape[0], manutencao.shape[1]))
manutencao.read()
