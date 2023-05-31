# Exemplo de teste de integração com Junit 5.

<br>
- O projeto foi desenvolvido no NetBeans deve ser chamado figuras_teste5_integracao.<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 5.<br>
- O teste de integração ocorre no teste unitário TestDesenho que integra as classe Desenho e as classe Triangulo e Retangulo.<br>
- A classe Desenho agrupa figuras (Triangulo e/ou Retangulo) em uma lista. Este classe possui o método getArea que permite retornar a área total de todas as figuras do desenho.<br>
- As classes Triangulo e Retangulo já foram testadas isoladamente através de testes unitários. <br>
- O teste unitário TestDesenho contêm duas operações de teste de integração:<br>
  -- testGetAdicionar() que irá testar a inclusão de uma figura<br>
  -- testGetArea() que irá testar a soma das áreas das figuras do desenho.<br>
