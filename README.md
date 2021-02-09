# Descrição.
 
Quando um sinal da PMT passa de um determinado valor de amplitude a sua informação começa a ser perdida, por causa da representação numérica da eletrônica da aquisição de dados do experimento. Por este motivo, o trabalho visa encontrar um modelo de machine learning que visa corrigir este problema.
 
Para encontrar os parâmetros utilizados para treinar e avaliar o modelo de machine learning. Foi montado em laboratório uma bancada que permitiu medir os sinais que provêm da PMT e que perderam a sua precisão na sua representação numérica. Para que assim seja possível extrair parâmetros deles e treinar um modelo de machine learning.
 
Sendo assim, temos 4 jupyter notebooks:
 
* Experimento: Nele contém o método atual utilizado pelo experimento para resolver o problema de representação numérica (Só está faltando adicionar este algoritmo).
* Comp_sinais: Adicionar as demais características impostas pela eletrônica de aquisição de dados do Experimento Neutrinos Angra aos sinais adquiridos em laboratório.
* ext_sinais: Avaliação de variáveis que possam ser utilizadas para treinar e avaliar o modelo de machine learning.
* Estimando_os_sinais: Modelando os modelos de machine learning, no caso um modelo de regressão baseado no polinomial e outro é uma rede Perceptron multicamadas. Depois eles foram avaliados junto com o método utilizado para experimento.
