# Testes de Software em .NET

## Introdução

Este documento descreve a implementação e os resultados dos testes de conversão de temperaturas de Fahrenheit para Celsius, empregando os frameworks xUnit, NUnit e MSTest no .NET 5. O objetivo destes testes é validar a precisão e eficácia da funcionalidade de conversão implementada.


## Ferramentas de Teste Utilizadas

**1. xUnit**

   - Descrição: O xUnit é um framework de teste para .NET conhecido por sua simplicidade e capacidade de extensão. É bem adequado para aqueles que valorizam uma interface de usuário limpa e a possibilidade de expansão através de plugins.

   - Funcionalidades: Suporta testes orientados a dados e executa testes em paralelo por padrão.

   - Resultados: Todos os 6 testes foram executados com sucesso em apenas 2 ms, demonstrando a eficiência do xUnit em processar testes rapidamente.


**2. NUnit**

   - Descrição: O NUnit é um framework amplamente utilizado por sua robustez e adaptabilidade, especialmente eficaz para testes detalhados e orientados a dados.

   - Funcionalidades: Facilita a implementação de testes unitários que são escaláveis e fáceis de manter.

   - Resultados: A execução dos 6 testes foi concluída com êxito em 7 ms, validando diversas entradas de temperatura com precisão.

**3. MSTest**

   - Descrição: MSTest é integrado ao Visual Studio e é ideal para usuários deste IDE. Oferece um bom suporte para execução paralela, apesar de ser menos versátil para testes orientados a dados em comparação com seus pares.

   - Resultados: Todos os 6 testes foram realizados com sucesso em 11 ms, o que indica uma boa performance, apesar de uma execução ligeiramente mais lenta comparada aos outros frameworks.

## Conclusão

A implementação dos testes de conversão de temperatura foi bem-sucedida usando xUnit, NUnit, e MSTest. Cada framework provou suas vantagens, com cada um exibindo características únicas que podem atender a diferentes necessidades e preferências de projeto.