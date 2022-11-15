# CNN - Keras - Visualizando Ativações das Camadas

Notebook para demonstrar como utilizar a API Keras para visualizar as ativações de uma CNN.

Neste notebook criamos um modelo para identificar dígitos usando a base do MNIST.

Após treinar e validar o modelo, podemos escolher quais camadas iremos visualizar e criar um modelo customizado usando `keras.models.Model`.
Esse modelo retorna um array com o output de todas as camadas quando o métedo `predict` é chamado.

Cada elemento do array é output de uma camada, podendo este ser um array de outputs (filtros de uma convolução) ou um output de uma camada densa.

Com esse esse array, podemos simplesmente exibir.
