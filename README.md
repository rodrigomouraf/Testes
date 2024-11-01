# Testes

Nesse documentos iremos abordar sobre os testes de software, hoje temos algumas categorias gerais sobre testes de software, sendo elas:

1. Testes de unidade
2. Testes de integração
3. Testes funcionais
4. Testes de ponta a ponta
5. Testes de aceitação
6. Testes de desempenho
7. Teste de fumaça (smoke test)

Para mais informações verifique https://www.atlassian.com/br/continuous-delivery/software-testing/types-of-software-testing

Os teste que eu mais vejo acontecendo hoje no mercado são os testes: unidade, integração e ponta a ponta (e2e).

1. Teste de Unidade (Base da Pirâmide)
Proporção Sugerida: Cerca de 70-80% dos testes automatizados.
Descrição: A base da pirâmide é formada por testes de unidade, que são rápidos, isolados e cobrem pequenos blocos de código (funções, métodos, classes).
Motivo: Como são os mais rápidos e baratos de executar, uma grande quantidade de testes de unidade aumenta a confiabilidade do código de forma eficiente e detecta a maioria dos erros cedo no processo de desenvolvimento.
2. Teste de Integração (Meio da Pirâmide)
Proporção Sugerida: Cerca de 15-20% dos testes.
Descrição: Esses testes garantem que os módulos ou serviços funcionam corretamente quando combinados e interagem conforme o esperado.
Motivo: Os testes de integração são mais lentos e complexos do que os de unidade, pois verificam múltiplos componentes, mas são importantes para validar que a comunicação entre as partes do sistema é bem-sucedida.
3. Teste de ponta a ponta (E2E) (Topo da Pirâmide)
Proporção Sugerida: Cerca de 5-10% dos testes.
Descrição: Testes E2E simulam o fluxo completo de um usuário no sistema, verificando que todos os componentes trabalham bem juntos em um cenário realista.
Motivo: São os testes mais lentos, caros e complexos, devido à necessidade de replicar o ambiente de produção e envolver várias camadas do sistema. Uma quantidade menor de testes E2E bem escolhidos ajuda a garantir a cobertura dos fluxos críticos sem sobrecarregar o processo de CI/CD.
Por que seguir essa proporção?
Seguir essa proporção oferece uma boa cobertura de testes com eficiência. Testes de unidade, que são rápidos e baratos, cobrem a maioria dos cenários e garantem a qualidade das partes menores do código. Testes de integração e E2E complementam essa cobertura, certificando que os componentes funcionam bem juntos e que os fluxos principais estão funcionando do início ao fim.

A pirâmide de testes, então, serve como um guia para equilibrar a cobertura com a complexidade e o custo dos testes, garantindo que os testes automatizados sejam efetivos e sustentáveis ao longo do tempo
https://martinfowler.com/articles/practical-test-pyramid.html
https://www.youtube.com/watch?v=IFzl5yWjbb4&list=PLzehOqhpwpxjs8bfI72dR-wV-7ZGxfuTN&index=3
https://medium.com/gtsw/a-pir%C3%A2mide-de-teste-e-os-testes-end-to-end-38f77ad3d137
https://medium.com/@jenifersilva/mergulhando-nos-testes-%C3%A1geis-com-janet-gregory-e-lisa-crispin-e1d1fac83794
