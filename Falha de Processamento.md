## Falha de Processamento do Código

<p align="justify">
A que você compartilhou mostra que o modelo está sempre prevendo a classe "leonard" (índice 1), mesmo quando as probabilidades para as outras classes são relativamente próximas.
Isso indica que o modelo está enviesado para prever "leonard", o que pode ser causado por problemas no treinamento, desequilíbrio nos dados ou configuração incorreta do modelo.
</p>

### Análise da saída:

**1. Previsões do modelo:**
- As probabilidades para cada classe são:
<p align="center">
<img
src="imagem/fig1 - falha de processamento.png"
    width="300"
/>
</p>

- Apesar de as probabilidades estarem relativamente próximas, o modelo sempre escolhe a classe 1 ("leonard") porque ela tem a maior probabilidade.

**2. Problema identificado:**

- O modelo não está confiante em suas previsões, já que as probabilidades estão muito próximas.

- O enviesamento para "leonard" pode ser causado por:

    - Desequilíbrio no conjunto de treinamento (muitas imagens de "leonard").

    - Problemas na função de perda ou no treinamento do modelo.

    - Configuração incorreta da camada de saída.

### Possíveis causas:

**1. Desequilíbrio no conjunto de treinamento:**

- Se o conjunto de treinamento tiver muitas mais imagens de "leonard" do que dos outros personagens, o modelo pode ter aprendido a prever sempre "leonard"
  para minimizar a perda.

**2. Problemas no treinamento:**
  - O modelo pode não ter sido treinado por tempo suficiente ou com uma taxa de aprendizado adequada.

**3. Configuração incorreta da camada de saída:**
-  A camada de saída deve ter 4 neurônios (um para cada classe) e usar a função de ativação softmax.

**4. Pré-processamento inconsistente:**
-  Se as imagens de entrada não estiverem sendo pré-processadas da mesma forma que as imagens de treinamento, o modelo pode não conseguir fazer previsões corretas.

### Conclusão
<p>
Este projeto está apresentando <b>erro de detecção e classificação</b>, não atingindo em sua completude a tarefa solicitada pelo professor. Apesar de direcionar esforço e energia para resolver os problemas apresentados na execução do código, não consegui resolver o problema.
</p>


  
