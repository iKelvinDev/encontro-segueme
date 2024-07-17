# encontro-segueme - Aplicativo Mobile

## Descrição do Aplicativo

O arquivo `descricao-telas.docx` contém descrições detalhadas e capturas de tela das interfaces criadas no Figma.

[Baixar descricao-telas.docx](./descricao-telas.docx)

## Diagrama UML

Abaixo está o diagrama UML que descreve a arquitetura básica do aplicativo:

![Diagrama UML](./uml-diagram.jpg)

### Descrição das Conexões no Diagrama:

**React Native -> Node.js:**

O aplicativo mobile (React Native) se comunica com o backend (Node.js) via requisições HTTP/HTTPS para enviar e receber dados.

**Node.js -> MySQL:**

O backend (Node.js) se comunica com o banco de dados (MySQL) usando comandos SQL para ler e escrever dados conforme necessário.

Esse diagrama simples mostra a estrutura básica e as conexões principais entre os componentes da aplicação mobile, o backend e o banco de dados.
