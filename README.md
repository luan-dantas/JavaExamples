# Creating the README content in markdown format

readme_content = """
# Java Examples

Este repositório contém exemplos de código em Java que desenvolvi durante o meu aprendizado da linguagem. Cada diretório inclui diferentes tópicos e conceitos fundamentais de Java, abordados em exercícios, projetos e testes práticos.

## Conteúdo

- **Introdução ao Java**
  - Estrutura básica de um programa Java
- **Tipos de Dados e Variáveis**
  - Tipos primitivos
  - Conversões de tipo
  - Variáveis locais e globais
- **Estruturas de Controle**
  - Condicionais: `if`, `else`, `switch`
  - Laços de repetição: `for`, `while`, `do-while`
- **Funções e Métodos**
  - Métodos com e sem retorno
  - Passagem de parâmetros
- **Orientação a Objetos**
  - Classes e Objetos
  - Herança, Polimorfismo, Abstração e Encapsulamento
  - Interfaces e classes abstratas
- **Coleções em Java**
  - Listas, Conjuntos, Filas e Mapas
- **Tratamento de Exceções**
  - Try-catch-finally
  - Exceções personalizadas
- **Projetos práticos**
  - Pequenos projetos para consolidar o aprendizado

## Como Usar

1. Clone o repositório:

\`\`\`bash
git clone https://github.com/seu-usuario/java-examples.git
\`\`\`

2. Navegue até o diretório de exemplos:

\`\`\`bash
cd java-examples
\`\`\`

3. Abra o exemplo que deseja estudar. Cada pasta contém um README adicional explicando o propósito do código.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Contato

Se tiver dúvidas ou sugestões, pode me contatar via [seu-email@example.com].
"""

# Save it as a markdown file
file_path = '/mnt/data/README.md'
with open(file_path, 'w') as file:
    file.write(readme_content)

file_path
