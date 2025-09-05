# bertoti

## Livro Software Engineering at Google
Trecho 1:
A diferença entre engenharia de sofware e programação. Muitas vezes esses dois termos são usados como sinônimos, mas são diferentes. Enquanto programação é o simples ato de escrever códigos, a engenharia de software tem um tom mais sério. Não é só a escrita do código, mas a prática de mantê-lo. Ela garante que os códigos se mantenham atualizados, funcionais e seguros ao longo do tempo. Diferente das outras engenharias, a engenharia de software trabalha com algo intangível. Por muito tempo ela foi tratada com pouco rigor, uma vez que errar um código tem consequências menos danosas do que errar o cálculo de um prédio ou um avião, por exemplo. Mas conforme softwares tem se tornado mais presentes e importantes nas nossas vidas, surge a necessidade de torná-la mais rigorosa.

Trecho 2:
Mas como podemos tornar a engenharia de software mais rigorosa? Tem três princípios que a engenhairos de software precisam ter em mente quando fazem o design, arquitetam e escrevem seus códigos:

- Tempo: Como um código vai precisar se adaptar ao decorrer de sua vida
- Escala: Como uma organização vai precisar se adaptar conforme cresce para 
- Trade-offs: Como uma organização toma decisões baseada nas lições dos dois anteriores

## Três exemplos de trade-offs
1. Desempenho vs. Manutenibilidade
  - Desempenho: Melhorar o desempenho do sistema (como otimizar algoritmos, usar técnicas avançadas de cache ou paralelismo) pode tornar o código mais complexo e difícil de entender.
  - Manutenibilidade: Para melhorar a manutenibilidade, o código deve ser mais simples, modular e bem documentado, o que pode levar a uma perda de desempenho. Por exemplo, o uso excessivo de abstrações pode reduzir o desempenho.

Trade-off: O engenheiro de software precisa decidir entre ter um código mais rápido e eficiente ou um código mais fácil de entender e manter a longo prazo.

2. Segurança vs. Usabilidade
  - Segurança: Implementar medidas de segurança rigorosas (como criptografia, autenticação multifatorial, etc.) pode complicar a experiência do usuário, tornando o sistema mais difícil de usar ou mais lento.
  - Usabilidade: Um sistema fácil de usar tem interfaces mais simples e menos passos para acessar recursos, mas pode ser mais vulnerável a ataques e falhas de segurança, pois pode não ter camadas de proteção adequadas.

Trade-off: Em sistemas de software, é preciso equilibrar a segurança necessária para proteger os dados dos usuários com a facilidade de uso do sistema, sem causar frustração ou confusão.

3. Custo vs. Qualidade
  - Custo: Desenvolver um software com menos recursos financeiros pode levar a escolhas como código mais simples, menos testes e prazos mais apertados, o que pode comprometer a qualidade.
  - Qualidade: Investir mais tempo e dinheiro em testes, revisões de código e boas práticas de desenvolvimento pode resultar em um produto mais robusto e livre de falhas, mas isso aumenta o custo de desenvolvimento.

Trade-off: É necessário balancear as restrições orçamentárias com a necessidade de entregar um software de alta qualidade, onde o custo pode impactar diretamente no nível de qualidade do produto final.

## Diagrama de classes UML
<img src="/engenhariadesoftware/img/UML.png">

## Código
<img src="/engenhariadesoftware/img/Sorveteria.png">
<img src="/engenhariadesoftware/img/Sorvete.png">
<img src="/engenhariadesoftware/img/Cobertura.png">

## Teste
<img src="/engenhariadesoftware/img/Teste.png">

## Diagrama de classes UML
<img src="/engenhariadesoftware/img/UML2.png">

## Código
<img src="/engenhariadesoftware/img/Cinema.png">
<img src="/engenhariadesoftware/img/Filme.png">

## Teste
<img src="/engenhariadesoftware/img/Teste2.png">
