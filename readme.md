## Notebook entrega os 5 algoritmos exigidos (KNN, LogReg, Decision Tree, Random Forest, SVM) com avaliação completa e comparação.

•⁠  ⁠Tudo roda limpo após Restart & Run All, sem warnings

### 1️⃣ Célula 0 – Seed global
 • Fixa SEED = 42 em Python, NumPy e sistema → garante resultados iguais sempre que rodar.

### 2️⃣ Célula 1 – Imports + Leitura
 • Importa Pandas, libs do sklearn e cinco algoritmos.
 
 • Lê o CSV Atividade_Cap_14_produtos_agricolas.csv e exibe as 5 primeiras linhas.

### 3️⃣ Célula 2 – Pré-processamento

 • Separa X (N, P, K, temperature, humidity, pH, rainfall) e y (label).
 
 • Codifica rótulos com LabelEncoder.
 
 • Divide treino/teste (80 / 20) estratificado.
 
 • Normaliza features com MinMaxScaler.
 
 • Mostra shapes + lista de culturas.

### 4️⃣ Célula 3 – KNN (k = 7)

 • Treina KNeighborsClassifier.
 
 • Calcula accuracy e relatório de métricas.

### 5️⃣ Célula 4 – Regressão Logística

 • Treina LogisticRegression (max_iter = 300).
 
 • Exibe accuracy + classification report.

### 6️⃣ Célula 5 – Árvore de Decisão

 • Treina DecisionTreeClassifier (random_state = 42).
 
 • Avalia accuracy + relatório.

### 7️⃣ Célula 6 – Random Forest

 • Treina RandomForestClassifier (200 árvores).
 
 • Mostra accuracy + métricas.

### 8️⃣ Célula 7 – SVM (kernel RBF)

 • Treina SVC(C=10, gamma='scale').
 
 • Exibe accuracy + relatório.

### 9️⃣ Célula 8 – Comparativo & Matriz de Confusão

 • Compila accuracies de todos os 5 modelos em tabela ordenada.
 
 • Identifica o modelo campeão.
 
 • Plota matriz de confusão do vencedor para ver acertos/erros por cultura.
