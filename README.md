# modulos_
#Manipulação de Matrizes

import numpy as np
m1=np.array(10) #dimensão zero - um número
m2=np.array([1,2,3,4]) #dimensão um vetor, tamanho 4.
m3=np.array([[1,2,3], [4,5,6]]) #matriz 2x3
m4=np.array([[[1,2,3], [4,5,6]], [[7,8,9], [10,11,12]]]) #matriz 2x2x3

print(m4*2)

#Interatividade

import numpy as np
mat=np.array([[[2,14,8,1], [17,4,13,9]], [[10,5,11,18], [26,19,23,16]], [[15,6,27,3], [12,20,0,21]]]) #2x2x4
print(mat[1, 0, 3] * 2)
