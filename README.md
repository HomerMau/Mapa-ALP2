# Programa de Gestão de Vacinas - UNICESUMAR

Este programa em C foi desenvolvido como parte de um desafio acadêmico durante a disciplina de Algoritmos e Lógica de Programação II, no curso de graduação da UNICESUMAR. O objetivo do programa é realizar o cadastro e gerenciamento de informações relacionadas à aplicação de vacinas contra a COVID-19.

## Descrição do Problema

A vacinação contra a COVID-19 é uma preocupação global, e a UNICESUMAR está buscando desenvolver um sistema de gerenciamento de vacinas para auxiliar na campanha de imunização. O desafio consiste em desenvolver um programa em C que seja capaz de cadastrar e consultar as informações das vacinas aplicadas.

O programa deve permitir o cadastro das seguintes informações de cada paciente e sua respectiva vacinação:
- Código (gerado automaticamente pelo programa)
- Nome do paciente
- CPF do paciente
- Nome da vacina aplicada
- Data da aplicação da vacina
- Número do lote da vacina

Além disso, o programa deve oferecer duas funcionalidades principais. A primeira é a geração de um relatório geral de todas as aplicações de vacinas, exibindo as informações cadastradas em formato de lista. A segunda funcionalidade é a busca por CPF, onde o usuário poderá consultar as informações de vacinação de um paciente específico.

## Funcionalidades e Menu de Opções

O programa conta com as seguintes funcionalidades e um menu interativo de opções:

1. **Cadastrar Vacina**: Permite realizar o cadastro das informações de aplicação de uma vacina para um paciente.
2. **Listar Aplicações**: Gera um relatório geral das aplicações de vacina, exibindo todas as informações cadastradas até o momento.
3. **Consultar por CPF**: Permite buscar as informações de vacinação de um paciente específico através do CPF.
4. **Sair**: Encerra o programa.

O programa utiliza conceitos de algoritmos e lógica de programação para implementar o controle de fluxo, estruturas de dados e entrada/saída de dados.

## Observações

- É importante ressaltar que o programa foi desenvolvido durante a disciplina de Algoritmos e Lógica de Programação II, na UNICESUMAR. Portanto, o foco principal do código é demonstrar o entendimento desses conceitos e não necessariamente representa uma solução completa e otimizada para um sistema real de gerenciamento de vacinas.
- Algumas melhorias podem ser feitas no código, como substituir a função `gets()` por `fgets()` para evitar possíveis problemas de estouro de buffer, e revisar o uso de `fflush(stdin)` que pode ser indefinido em fluxos de entrada.
- O uso de `goto` pode ser considerado uma prática de programação ruim, tornando o código menos legível e difícil de dar manutenção. Em projetos reais, é recomendado utilizar estruturas de controle mais adequadas, como `if-else` e `while`, para controlar o fluxo do programa.