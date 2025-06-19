Como já dizia Eduardo Galeano: "Cada bola que encosta na rede de um clube europeu é um dente a mais no sorriso de um torcerdor latino-americano"


**Simulação de Probabilidade usando o metodo de Monte Carlo no Grupo B da FIFA World Cup**

Basicamente, usei o método de Monte Carlo (que é tipo jogar dados um milhão de vezes pra ver no que dá) pra simular todos os resultados possíveis dos jogos restantes do Grupo B. A partir dos dados atuais da tabela e das probabilidades baseadas nas ODDs, o código roda milhares de cenários e me diz, em porcentagem, qual a chance real do Botafogo terminar em 1º ou 2º e seguir pra próxima fase.

**Estrutura do notebook**

*   **DataFrame do Grupo B** Os dados iniciais com as informações até o presente momento (19/06/2025) antes das simulações.
*   **As ODDs** Como as probabilidades dos resultados dos jogos restantes foram definidas (Retirei do site Sofascore).
*   **Expectativa de Gols:** Uma forma de prever quantos gols podem sair em cada jogo (utilizei a média de ODDs, para simplificar o processo).
*   **A Simulação dos jogos** O centro do projeto, onde milhares de jogos são simulados.
*   **O destino até o ponto Y(A Classificação)** Como a tabela final é calculada em cada simulação.
*   **Os Números Finais:** As probabilidades calculadas de classificação do Botafogo e dos outros times.
*   **Gráficos** Uma visualização das simulações.

**BFR - ⭐️**
