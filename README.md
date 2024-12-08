# ListaPackage - Script Oracle

## Como executar o script no Oracle:

1. **Criação do Banco de Dados**:
   - O script contém a criação de tabelas como `ALUNO`, `CURSO`, `DISCIPLINA`, `MATRICULA`, entre outras, que são necessárias para o funcionamento do sistema.
   - Antes de executar o script, certifique-se de que o banco de dados Oracle está configurado e funcionando.

2. **Execução do Script**:
   - Faça login no Oracle SQL*Plus ou no Oracle Live SQL.
   - Importe ou cole o conteúdo do arquivo `script.sql` no ambiente.
   - Execute as instruções para criar as tabelas, pacotes e as funcionalidades associadas.

3. **Testando as funcionalidades**:
   - Após a criação das tabelas e pacotes, você pode rodar os blocos de código de teste para verificar se as procedures e funções estão funcionando corretamente.
   - A execução do código de teste irá cadastrar uma disciplina e listar os alunos associados a ela.

## Resumo dos Pacotes:

### **PKG_ALUNO**:
- **Excluir aluno**: Exclui um aluno e suas matrículas associadas.
- **Listar alunos maiores de 18 anos**: Exibe os alunos com mais de 18 anos.
- **Listar alunos por curso**: Exibe os alunos de um determinado curso.

### **PKG_DISCIPLINA**:
- **Cadastrar disciplina**: Insere uma nova disciplina no banco de dados.
- **Listar alunos por disciplina**: Exibe os alunos matriculados em uma disciplina específica.
- **Média de idade por disciplina**: Calcula a média de idade dos alunos de uma disciplina.
- **Total de alunos por disciplina**: Retorna a quantidade de alunos matriculados em disciplinas com mais de 10 alunos.

## Repositório GitHub

- Este repositório contém o script completo para criação e teste das tabelas e pacotes no Oracle.
- A execução correta do script cria as tabelas e pacotes necessários para o gerenciamento de alunos, cursos e disciplinas.

## Como usar o repositório

1. Clone este repositório para seu ambiente local.
2. Execute o script SQL conforme descrito acima.
3. Faça os testes necessários para garantir que as funcionalidades estão operando conforme esperado.

