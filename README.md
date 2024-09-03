<h1 align="center">Formulário em React com Hooks</h1>


Este projeto demonstra como trabalhar com formulários em React usando os hooks `useState` para gerenciar o estado dos campos do formulário e o resultado do processamento do formulário. 

### Funcionalidades do Demo

- **Gerenciamento de Estado:** Utiliza o `useState` para controlar os valores dos campos de entrada (nome e sobrenome) e o nome completo gerado.
- **Manipulação de Eventos:** Inclui funções para capturar as mudanças nos campos (`handleInputChange`) e para processar o envio do formulário (`handleFormSubmit`).
- **Atualização do Estado:** Ao enviar o formulário, o nome completo é exibido abaixo do formulário.

### Estrutura do Código

1. **Estados Definidos:**
   - `formData`: Armazena os valores dos campos `firstName` e `lastName`.
   - `fullName`: Exibe o nome completo gerado após o envio do formulário.

2. **Manipulação do Formulário:**
   - `handleInputChange`: Atualiza o estado `formData` com os valores digitados pelo usuário.
   - `handleFormSubmit`: Concatena o primeiro e o último nome e atualiza o estado `fullName`.

3. **Renderização:**
   - Um formulário com campos para nome e sobrenome e um botão de envio.
   - O nome completo é exibido após o envio do formulário.

### Como Executar o Projeto

1. Clone o repositório:
   ```bash
   
   git clone git@github.com:wellingtonrsdev/introducao-form-react.git

2. Instale as dependências:

    ```bash
   yarn 

3. Executar o projeto:

   ```bash
   yarn dev

Esse projeto é um exemplo prático de como capturar e exibir dados de formulários em uma aplicação React de forma simples e eficiente.


