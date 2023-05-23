# MLP-or-TensorFlow
Criado para comparar a capacidade, assertividade e complexidade de modelos MLP ou com bibliotecas especializadas em ML 
# Comparando
As duas implementações usam técnicas semelhantes para resolver o mesmo problema, mas com algumas diferenças nas etapas de pré-processamento e modelagem.

Na primeira implementação, pré-processamos manualmente os dados dimensionando os recursos e codificando a variável de destino. Em seguida, criamos um modelo de rede neural do zero usando NumPy e o treinamos usando retropropagação com uma taxa de aprendizado fixa.

Na segunda implementação, usamos as classes StandardScaler e OneHotEncoder do Scikit-learn para pré-processar os dados. Criamos um modelo de rede neural usando a classe Sequential do TensorFlow e adicionamos camadas a ele usando a classe Dense. Usamos o otimizador Adam para treinar o modelo e avaliá-lo no conjunto de teste usando o método de avaliação.

Os parâmetros usados nas duas implementações são semelhantes, mas não exatamente iguais. Por exemplo, na primeira implementação, usamos uma taxa de aprendizado de 0,1, enquanto na segunda implementação usamos a taxa de aprendizado padrão do otimizador Adam. Da mesma forma, na primeira implementação, usamos uma camada oculta com 10 neurônios, enquanto na segunda implementação usamos duas camadas ocultas com 10 neurônios cada.

Pode haver uma diferença de desempenho entre as duas implementações, dependendo do tamanho e complexidade do conjunto de dados e da arquitetura do modelo. Em geral, as bibliotecas de ML, como Scikit-learn e TensorFlow, são projetadas para serem altamente otimizadas e eficientes, de modo que muitas vezes podem ter um desempenho melhor do que as implementações manuais.

A implementação de uma solução sem uma biblioteca de ML pode ajudar a entender como funciona uma função de biblioteca de ML e os conceitos subjacentes do aprendizado de máquina. Também pode ajudar a desenvolver uma melhor intuição sobre os hiperparâmetros e seu impacto no desempenho do modelo. No entanto, usar uma biblioteca de ML pode economizar muito tempo e esforço na implementação e teste de diferentes modelos e, muitas vezes, pode levar a melhores resultados com menos esforço.
