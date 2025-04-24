# DCL AnyGrid 🚀

Bem-vindo ao projeto **DCL AnyGrid**! Esta aplicação em React permite aos usuários gerar uma **Declaração para Transporte de Mercadoria (DCL)**, oferecendo um formulário intuitivo para preenchimento das informações do remetente, destinatário e detalhes dos itens. 📄

## Funcionalidades 🌟

- **Formulário Interativo**: Interface amigável para inserir dados do remetente, destinatário e itens, com campos de entrada que se adaptam ao tamanho da tela.
- **Máscaras de Entrada**: Utilização de máscaras para garantir que as informações sejam inseridas corretamente (CNPJ, CEP, Telefone, etc.).
- **Geração de PDF**: Criação de um PDF formatado com todas as informações preenchidas, pronto para download. 📥
- **Validação de CEP**: Busque automaticamente informações de endereço ao inserir um CEP válido, facilitando o preenchimento.

## Tecnologias Utilizadas 🛠️

- **React**: Biblioteca popular para construção de interfaces de usuário.
- **pdf-lib**: Biblioteca que permite a criação e manipulação de arquivos PDF.
- **react-input-mask**: Utilizada para aplicar máscaras de entrada nos campos do formulário.

## Estrutura do Código 📂

O código principal do formulário está localizado no arquivo `DclForm.js`. Aqui estão alguns dos principais componentes e funções:

- **Estados**: Utilizamos o `useState` para gerenciar os dados do formulário, como informações do remetente, destinatário e itens.
- **Fetch CEP**: A função `fetchCepData` busca informações de endereço a partir do CEP inserido, utilizando uma API externa.
- **Manipulação de Itens**: Funções para adicionar, remover e atualizar os itens da lista, permitindo um gerenciamento dinâmico dos dados.
- **Geração de PDF**: A função `generatePdf` cria um documento PDF com as informações inseridas, formatando adequadamente o conteúdo.

  ## Preencha o Formulário:
 - **Remetente**: Insira os dados do remetente, incluindo nome, CNPJ, endereço, cidade, UF, CEP e contato.
 - **Destinatário**: Preencha as informações do destinatário com os mesmos campos.
 - **Itens**: Adicione os itens que serão transportados, incluindo quantidade, descrição, código do produto e peso.
 - **Valor** Simbólico: Insira o valor simbólico do transporte.
 - **Gerar DCL**: Clique no botão "Gerar DCL" para baixar o PDF com todas as informações.

 - ![img-sistema](https://github.com/user-attachments/assets/70156344-94c9-4c61-a20a-368b149fc7f8)







   
