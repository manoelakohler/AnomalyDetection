# Palestra Detecção de Anomalias - BI Master PUC-Rio
## Scripts desenvolvidos para palestra para alunos do curso BI Master

[Você pode acessar o código da solução aqui!](https://github.com/manoelakohler/AnomalyDetection/blob/main/AnomalyDetection.ipynb)

### Índice
  
- [O Problema](#o-problema)
- [A solução](#a-solução)

<h2 id="o-problema">

[O Problema](https://github.com/manoelakohler/AnomalyDetection/blob/main/AnomalyDetection.ipynb)
  
</h2>

![image](https://user-images.githubusercontent.com/11425838/178998129-142d0b3c-c5a8-42f5-8643-9a3f2daea9bd.png)


<h2 id="a-solução">

[A Solução](https://github.com/manoelakohler/AnomalyDetection/blob/main/AnomalyDetection.ipynb)
  
</h2>

 Exemplos de ECG anômalos e normais:
 
 ![image](https://user-images.githubusercontent.com/11425838/178998499-beea45ed-bd47-41da-b78d-10a2772a7292.png)


Modelo Treinado:

![image](https://user-images.githubusercontent.com/11425838/178998643-69ad0cbf-8ccc-438a-9958-bc5d5d176968.png)


Loss do Modelo (treino e validação):

![image](https://user-images.githubusercontent.com/11425838/178998736-c35dc27d-4b46-4587-8d32-c0b69ed7f904.png)


Reconstrução de um ECG aleatório da base de teste:

![image](https://user-images.githubusercontent.com/11425838/178998847-0cff0a7f-85d7-41b4-a9c6-1e80bb46d107.png)

Dispersão dos erros por classe (Anomalia ou Normal) e threshold definido para classificação:

![image](https://user-images.githubusercontent.com/11425838/178999023-d8a4c235-967f-46f7-8ed8-26e0ceb6dccd.png)

Métricas para base de teste:

![image](https://user-images.githubusercontent.com/11425838/178999110-f9199417-a86a-45be-a17b-c2df6ef9eac9.png)

