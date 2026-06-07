# Codigo-Limpo
Um resumo feito após a leitura e interpretação do livro Codigo limpo de Robert C. Martin

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Código Limpo - Autor: Robert C. Martin(Resumo: Capítulo 2,4,5)  
### Aluno: Gabriel Melo Bussolo    Curso: Engenharia de Software  
### Instituição: Unibave  
  
#### Nomeação Significativa  
Este capítulo esclarece a necessidade de nomes bem elaborados para a declaração de variáveis;funções e classes sendo necessário cuidado para nomeá-los para não gerar confusão e principalmente a perda de tempo em revisões ou cansaço para o entendimento do código escrito. 
Sendo necessário buscar:  
- Nomes que revelem a função e propósito do código.   
 - Não utilizar nomes que camuflam ou escondem o significado do código.  
- Evitar diferenciar variáveis parecidas apenas mudando números ou adicionando palavras redundantes.
 #### Comentarios 
Este capítulo busca mostrar ao leitor que comentários muitas vezes são gastos de tempo e armazenamento desnecessários , pois simboliza o fracasso do programador em expressar a intenção através do próprio código. Também esclarece o pior fato envolvendo comentários onde o código muda e evolui, mas os comentários raramente são atualizados, tornando-se mentiras perigosas com o tempo ou sendo redundantes. Entretanto esses quesitos se tornam exceção nos seguintes casos:  
- Comentários legais/direitos autorais.  
- Explicações de decisões de design de negócios muito específicas ou algoritmos matemáticos complexos de terceiros/​Clarificação de retornos ou argumentos obscuros que você não pode alterar (de bibliotecas externas).  
- Alertas sobre o código ou consequências ao alterar determinado código.  
- Marcações de // TODO (desde que monitoradas e resolvidas frequentemente).
   
__Obs:__ Os comentários devem sempre serem  evitados ao máximo para não gerar desinformação ou poluição no código . Sendo necessário analisar se são realmente úteis e principalmente se não estão esclarecendo o óbvio ou sendo redundantes.

#### Formatação  
Este capítulo prova que a formatação de um código está totalmente ligada à sua legibilidade. Onde uma boa formatação contribui para uma a interpretação do código e para uma menor exaustão mental também demonstrando profissionalismo e cuidado com o código e comunicação da equipe desenvolvedora. Existem diversas maneira de se obter uma boa formatação de código uma delas é:
- __Formatação Vertical:__ Deve-se usar linhas em branco para separar conceitos ou blocos de pensamento diferentes (como funções ou variáveis). As linhas de código que possuem forte associação lógica devem ficar juntas variáveis locais devem ser declaradas o mais próximo possível de onde são usadas. Funções chamadas devem ficar logo abaixo da função que as chamou (afinidade conceitual).
  
__Obs:__ Um arquivo de código deve ser lido como um artigo de jornal. No topo, temos as informações gerais e conceitos de alto nível (títulos). Conforme descemos no arquivo, os detalhes de implementação vão aparecendo.  
- A formatação limpa e padronizada permite que o código seja escaneado visualmente, pois desenvolvedores experientes não leem o código caractere por caractere; eles batem o olho na estrutura anatômica do arquivo para entender o fluxo.  
- É de grande importância seguir o padrão de formatação adotado pela equipe (e não o gosto individual) para um bom código que parece ter sido escrito por uma única pessoa e mostrar ao leitor que há excelente sinergia e alinhamento estratégico entre a equipe.  





