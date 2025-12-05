# 📝 Lista de Tarefas (Task List)

Uma aplicação web simples e intuitiva para gerenciamento de tarefas diárias. Este projeto foi desenvolvido para praticar manipulação de DOM, estilização com CSS moderno e persistência de dados com LocalStorage.

![Preview do Projeto](https://github.com/VictorPrazeres/task-list/blob/main/image_fa5ac8.png?raw=true)

## 🚀 Funcionalidades

- **Adicionar Tarefas:** Campo de input com validação que impede a criação de tarefas vazias.
- **Marcar como Concluída:** Ao clicar no texto da tarefa, ela é riscada visualmente, indicando sua conclusão, e o status é salvo.
- **Excluir Tarefas:** Botão de lixeira com destaque visual (vermelho) para remover itens da lista permanentemente.
- **Persistência de Dados:** As tarefas são salvas no **LocalStorage** do navegador, garantindo que os dados não sejam perdidos ao atualizar a página.
- **Interface Responsiva:** Layout centralizado e adaptável.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica da página.
- **CSS3:**
  - Uso de **Flexbox** para alinhamento de elementos.
  - Background com **Linear Gradient**.
  - Transições suaves (`transition`) para interações.
- **JavaScript (ES6+):**
  - Manipulação do DOM (`document.createElement`, `appendChild`, `remove`).
  - `JSON.parse` e `JSON.stringify` para gerenciamento do LocalStorage.
- **Bibliotecas e Fontes:**
  - [FontAwesome](https://fontawesome.com/) (Ícones de lixeira).
  - [Google Fonts](https://fonts.google.com/) (Fonte *Poppins*).

## 📂 Como rodar o projeto

Este é um projeto estático, não requer instalação de dependências complexas.

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/VictorPrazeres/task-list.git](https://github.com/VictorPrazeres/task-list.git)
