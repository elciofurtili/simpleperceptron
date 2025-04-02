# 📚 Perceptron Simples - Classificação Binária 

Este projeto implementa um Perceptron Simples para classificação binária utilizando aprendizado supervisionado. O modelo ajusta seus pesos com base no erro das previsões e aplica uma regra de atualização linear. Este algoritmo pode ser utilizado em diversos cenários de classificação binária.

## 🚀 Características do Projeto

* **3 Datasets de Teste e Treinamento:** Inclui datasets 1, 2 e 3, preparados para treinar e testar o Perceptron.
* **Implementação do Perceptron:** Funções de treinamento e teste baseadas no algoritmo do Perceptron.
* **Visualização Gráfica:** Exibição do erro de treinamento ao longo das épocas e da fronteira de decisão.
* **Avaliação:** Cálculo da acurácia nos dados de treino e teste. ✅

## 🗂 Estrutura do Código

1.  **Função `train_perceptron`:** ⚙️

    Essa função treina o modelo Perceptron. Ela recebe:

    * `X`: Dados de entrada (atributos).
    * `y`: Rótulos de classe (1 ou -1). ️
    * `learning_rate`: Taxa de aprendizado. 
    * `epochs`: Número máximo de épocas para o treinamento. ⏳
    * `seed`: Semente para reprodutibilidade. 

    A função retorna:

    * `weights`: Pesos ajustados após o treinamento. ⚖️
    * `epoch`: Número de épocas executadas. ⏱️
    * `errors`: Lista de erros durante o treinamento. ❌

    ```python
    def train_perceptron(X, y, learning_rate=0.1, epochs=100, seed=None):
        # Implementação 
    ```

2.  **Função `test_perceptron`:** Avalia o desempenho do modelo no conjunto de dados de teste, retornando a acurácia do modelo.

    ```python
    def test_perceptron(X, y, weights):
        # Implementação 
    ```

3.  **Função `plot_decision_boundary`:** Exibe a fronteira de decisão do Perceptron, mostrando como o modelo classifica os dados em diferentes regiões.

    ```python
    def plot_decision_boundary(X_train, y_train, weights):
        # Implementação 
    ```

4.  **Execução do Código:** ▶️

    A execução envolve o carregamento dos dados, treinamento do modelo e avaliação. O código faz uso de Matplotlib para exibir gráficos da evolução do erro e das fronteiras de decisão.

## 📊 Datasets

Este projeto utiliza 3 datasets para treinar e testar o Perceptron:

* **Dataset 1:** Dados de treino e teste para a primeira tarefa de classificação. 1️⃣
* **Dataset 2:** Dados para a segunda tarefa de classificação. 2️⃣
* **Dataset 3:** Dados para a terceira tarefa de classificação. 3️⃣

Cada dataset é carregado de arquivos CSV e a avaliação é feita com base nas métricas de acurácia.

## 📥 Instalação e Uso

1.  **Requisitos:**

    Certifique-se de que você tem as seguintes dependências instaladas:

    ```bash
    pip install numpy pandas matplotlib 
    ```

2.  **Como Rodar:**

    * Clone o repositório (ou baixe os arquivos necessários):

        ```bash
        git clone [https://github.com/seu-usuario/perceptron.git](https://github.com/seu-usuario/perceptron.git) 
        cd perceptron 
        ```

    * Carregue os Dados: O código carrega automaticamente os arquivos `train_dataset1.csv`, `train_dataset2.csv` e `train_dataset3.csv` para treino, além dos arquivos `test_dataset1.csv`, `test_dataset2.csv` e `test_dataset3.csv` para teste.

        Se necessário, modifique o caminho dos arquivos CSV no código. ✍️

    * Execute o Código: Execute o script Python para treinar e testar o modelo:

        ```bash
        python perceptron.py ▶️
        ```

    * Visualização: O código gerará gráficos que mostram a evolução do erro durante o treinamento, além das fronteiras de decisão para cada dataset.

##  Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou correções, sinta-se à vontade para abrir uma issue ou enviar um pull request. 

##  Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato. 