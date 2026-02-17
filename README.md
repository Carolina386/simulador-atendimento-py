# 🚀 Simulador de Atendimento Python (v2.0)

Este projeto evoluiu de um fluxo linear para um **sistema de gestão de filas**, aplicando conceitos de estruturas de dados e preparando o terreno para estudos em bancos de dados.

## 🆕 Novidades desta Versão
Nesta atualização, o foco foi a transição para um **sistema com memória**, utilizando conceitos que estou estudando para o banco de dados **Hive** no Flutter.

- **Fila Dinâmica (FIFO):** Implementação de uma lista real onde os clientes entram e saem na ordem correta (*First-In, First-Out*).
- **Manipulação de Dados:** Uso de métodos `.append()` para entrada de novos clientes e `.pop(0)` para realizar o atendimento.
- **Modo Atendente (Opção 6):** Uma funcionalidade exclusiva para processar a fila, simulando o trabalho real de um caixa ou suporte.
- **Loop de Execução:** O sistema agora utiliza um laço `while`, permanecendo ativo para múltiplos atendimentos até que o comando 'sair' seja acionado.

## Tecnologias Utilizadas
- **Python 3**
- Lógica de Programação e Estruturas de Dados (Listas/Filas)

## 🧠 Insights de Aprendizado
Este upgrade foi fundamental para entender a **persistência temporária de dados** e como organizar informações em memória. A lógica de "adicionar e remover" da fila reflete exatamente o que pretendo implementar ao refatorar meus projetos Flutter de SQLite para **Hive (NoSQL)**.

## ▶️ Como executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/Carolina386/simulador-atendimento-py.git](https://github.com/Carolina386/simulador-atendimento-py.git)