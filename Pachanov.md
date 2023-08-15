# Boas Práticas no Python

## Indentação Consistente
Use espaços em branco para criar uma indentação consistente. O padrão é usar 4 espaços por nível de indentação.

## Nomes Descritivos de Variáveis e Funções
Utilize nomes que descrevam claramente o propósito da variável ou função. Evite abreviações obscuras.

## Comentários Explicativos
Comente o seu código para explicar partes complexas ou fornecer informações sobre o que um bloco de código está fazendo.

## Limite de Linha
Mantenha as linhas de código com até 79 ou 80 caracteres para garantir a legibilidade. O limite para comentários é 72 caracteres.

## Imports Organizados
Organize os imports em grupos separados (bibliotecas padrão, bibliotecas de terceiros, seus próprios módulos) e coloque-os no topo do arquivo.

## Evite Comentários Óbvios
Evite sobrecarregar o código com comentários que apenas explicam o óbvio, como "i = i + 1".

## Use List Comprehensions
Quando apropriado, use list comprehensions para criar listas de maneira mais concisa.

## Evite Linhas em Branco Desnecessárias
Não adicione linhas em branco extras onde elas não são necessárias. Isso ajuda a manter o código mais limpo.

## Não Use Imports Genéricos
Evite usar `import *` para importar todos os símbolos de um módulo. Isso pode poluir o namespace e dificultar a leitura.

## Usar Docstrings
Documente suas funções e classes usando docstrings para explicar seu propósito, parâmetros e retornos.

## Trate Exceções de Forma Adequada
Utilize blocos `try` e `except` para capturar e tratar exceções de forma apropriada, em vez de deixar o código quebrar.

## Evite Magia Número
Evite usar números mágicos diretamente em seu código. Em vez disso, atribua-os a variáveis com nomes descritivos.

## Usar `if __name__ == "__main__":` para Scripts
Utilize essa estrutura para permitir que um módulo Python seja executado como um script, mas também seja importado como um módulo em outro lugar.

## Usar `enumerate` em Loops
Use a função `enumerate` para obter tanto o índice quanto o valor de uma lista durante um loop.

## Evite Funções com Muitos Argumentos
Tente manter o número de argumentos das funções baixo para tornar o código mais legível e fácil de usar.

## Use Listas, Dicionários e Sets de Forma Apropriada
Escolha a estrutura de dados correta para o problema que você está resolvendo, seja uma lista, dicionário ou set.

**Descreva as Alternativas que Você Considerou**
Uma descrição clara e concisa de quaisquer soluções ou recursos alternativos que você considerou.

**Contexto Adicional**
Adicione qualquer outro contexto ou captura de tela sobre a solicitação de recurso aqui.
