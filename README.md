
# Projeto Gerenciador de Produtos Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-f7df1e?logo=javascript&logoColor=black&style=flat)
![React](https://img.shields.io/badge/React-18.x-61dafb?logo=react&logoColor=black&style=flat)

## Descrição

Frontend de um sistema para gerenciar produtos, desenvolvido com ReactJS e Vite.

## Tecnologias Utilizadas
- **ReactJS**
- **Vite**
- **JavaScript**

## Criação do Projeto

Para iniciar o projeto, utilize os seguintes comandos:

```bash
npm create vite@latest
# Escolha [React/JavaScript] como template
npm install
```

## Configuração do Backend Mockado

Durante o desenvolvimento das telas, será utilizado um backend mockado com o **json-server**. Para configurar, siga os passos abaixo:

1. Instale o json-server:
   ```bash
   npm install json-server@0.16.3
   ```

2. Crie uma pasta chamada `data` no projeto.

3. Dentro da pasta `data`, crie um arquivo chamado `db.json` para armazenar os dados mockados.
   
4. ### Estrutura inicial do arquivo `db.json`

```json
{
  "fornecedores": [
    {
      "nome": "Fornecedor WWW",
      "cnpj": "33232323232323",
      "email": "kelson.victr@gmail.com",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "58079-000",
        "logradouro": "Rua Deputado Francisco Seráphico da Nóbrega Filho",
        "numero": "383",
        "complemento": "CASA",
        "bairro": "Funcionários",
        "cidade": "João Pessoa",
        "estado": "PB",
        "pais": "Brasil"
      },
      "id": 6
    },
    {
      "nome": "Fornecedor XYZ",
      "cnpj": "12345678901234",
      "email": "contato@fornecedorxyz.com",
      "tipoFornecedor": "PREMIUM",
      "endereco": {
        "cep": "11015-000",
        "logradouro": "Avenida das Nações",
        "numero": "100",
        "complemento": "SALA 1",
        "bairro": "Centro",
        "cidade": "Santos",
        "estado": "SP",
        "pais": "Brasil"
      },
      "id": 7
    },
    {
      "nome": "Comercial Silva",
      "cnpj": "23456789012345",
      "email": "contato@comercialsilva.com.br",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "30110-000",
        "logradouro": "Rua São João",
        "numero": "200",
        "complemento": "",
        "bairro": "Lourdes",
        "cidade": "Belo Horizonte",
        "estado": "MG",
        "pais": "Brasil"
      },
      "id": 8
    },
    {
      "nome": "Distribuidora ABC",
      "cnpj": "34567890123456",
      "email": "vendas@abcdistribuidora.com",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "40150-000",
        "logradouro": "Estrada do Sol",
        "numero": "450",
        "complemento": "Bloco B",
        "bairro": "Pituba",
        "cidade": "Salvador",
        "estado": "BA",
        "pais": "Brasil"
      },
      "id": 9
    },
    {
      "nome": "Fornecedor Alfa",
      "cnpj": "45678901234567",
      "email": "contato@fornecedoralfa.com",
      "tipoFornecedor": "PREMIUM",
      "endereco": {
        "cep": "50740-000",
        "logradouro": "Rua das Palmeiras",
        "numero": "89",
        "complemento": "APTO 501",
        "bairro": "Boa Viagem",
        "cidade": "Recife",
        "estado": "PE",
        "pais": "Brasil"
      },
      "id": 10
    },
    {
      "nome": "Mega Fornecedores",
      "cnpj": "56789012345678",
      "email": "suporte@megafornecedores.com",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "69900-000",
        "logradouro": "Rua do Comércio",
        "numero": "11",
        "complemento": "Galpão 3",
        "bairro": "Centro",
        "cidade": "Rio Branco",
        "estado": "AC",
        "pais": "Brasil"
      },
      "id": 11
    },
    {
      "nome": "Fornecedor Delta",
      "cnpj": "67890123456789",
      "email": "delta@fornecedoresdelta.com",
      "tipoFornecedor": "PREMIUM",
      "endereco": {
        "cep": "57000-000",
        "logradouro": "Avenida Marítima",
        "numero": "255",
        "complemento": "",
        "bairro": "Ponta Verde",
        "cidade": "Maceió",
        "estado": "AL",
        "pais": "Brasil"
      },
      "id": 12
    },
    {
      "nome": "Grupo Nova Era",
      "cnpj": "78901234567890",
      "email": "contato@novafornecedores.com",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "88015-000",
        "logradouro": "Rua das Hortênsias",
        "numero": "60",
        "complemento": "",
        "bairro": "Centro",
        "cidade": "Florianópolis",
        "estado": "SC",
        "pais": "Brasil"
      },
      "id": 13
    },
    {
      "nome": "Mercantil Pereira",
      "cnpj": "89012345678901",
      "email": "atendimento@mercantilpereira.com",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "64000-000",
        "logradouro": "Avenida Getúlio Vargas",
        "numero": "700",
        "complemento": "Prédio A",
        "bairro": "Centro",
        "cidade": "Teresina",
        "estado": "PI",
        "pais": "Brasil"
      },
      "id": 14
    },
    {
      "nome": "Central de Fornecedores",
      "cnpj": "90123456789012",
      "email": "vendas@centralfornecedores.com",
      "tipoFornecedor": "PREMIUM",
      "endereco": {
        "cep": "72000-000",
        "logradouro": "Rua dos Pinhais",
        "numero": "300",
        "complemento": "Conjunto 10",
        "bairro": "Taguatinga",
        "cidade": "Brasília",
        "estado": "DF",
        "pais": "Brasil"
      },
      "id": 15
    },
    {
      "nome": "Fornecedor Global",
      "cnpj": "01234567890123",
      "email": "global@fornecedoresglobal.com",
      "tipoFornecedor": "COMUM",
      "endereco": {
        "cep": "80000-000",
        "logradouro": "Rua do Comércio Exterior",
        "numero": "1",
        "complemento": "",
        "bairro": "Centro",
        "cidade": "Curitiba",
        "estado": "PR",
        "pais": "Brasil"
      },
      "id": 16
    }
  ],
  "produtos": [
    {
      "id": 1,
      "nome": "Cadeira Ergonômica",
      "preco": "850.00",
      "descricao": "Cadeira para escritório com ajuste de altura.",
      "quantidadeEstoque": 20
    },
    {
      "id": 2,
      "nome": "Notebook Gamer",
      "preco": "5000.00",
      "descricao": "Notebook com alto desempenho para jogos.",
      "quantidadeEstoque": 10
    },
    {
      "id": 3,
      "nome": "Geladeira Inox",
      "preco": "3500.00",
      "descricao": "Geladeira com design moderno e capacidade ampla.",
      "quantidadeEstoque": 8
    },
    {
      "id": 4,
      "nome": "Smartphone 5G",
      "preco": "2800.00",
      "descricao": "Celular de última geração com suporte a 5G.",
      "quantidadeEstoque": 15
    },
    {
      "id": 5,
      "nome": "Fone de Ouvido Bluetooth",
      "preco": "250.00",
      "descricao": "Fone sem fio com excelente qualidade de som.",
      "quantidadeEstoque": 50
    }
  ],
  "clientes": [
    {
      "id": 1,
      "nome": "Carlos da Silva",
      "cpf": "123.456.789-10",
      "email": "carlos.silva@gmail.com",
      "cep": "01010-000",
      "rua": "Rua Central",
      "numero": "123",
      "bairro": "Centro",
      "cidade": "São Paulo",
      "estado": "SP",
      "pais": "Brasil"
    },
    {
      "id": 2,
      "nome": "Ana Maria Oliveira",
      "cpf": "987.654.321-00",
      "email": "ana.oliveira@hotmail.com",
      "cep": "02020-000",
      "rua": "Avenida Paulista",
      "numero": "456",
      "bairro": "Bela Vista",
      "cidade": "São Paulo",
      "estado": "SP",
      "pais": "Brasil"
    },
    {
      "id": 3,
      "nome": "João Pereira",
      "cpf": "111.222.333-44",
      "email": "joao.pereira@yahoo.com",
      "cep": "03030-000",
      "rua": "Rua das Flores",
      "numero": "789",
      "bairro": "Jardins",
      "cidade": "Rio de Janeiro",
      "estado": "RJ",
      "pais": "Brasil"
    },
    {
      "id": 4,
      "nome": "Mariana Santos",
      "cpf": "444.555.666-77",
      "email": "mariana.santos@gmail.com",
      "cep": "04040-000",
      "rua": "Praça das Águas",
      "numero": "101",
      "bairro": "Águas Claras",
      "cidade": "Curitiba",
      "estado": "PR",
      "pais": "Brasil"
    },
    {
      "id": 5,
      "nome": "Pedro Rodrigues",
      "cpf": "555.666.777-88",
      "email": "pedro.rodrigues@outlook.com",
      "cep": "05050-000",
      "rua": "Travessa dos Pássaros",
      "numero": "202",
      "bairro": "Vila Nova",
      "cidade": "Porto Alegre",
      "estado": "RS",
      "pais": "Brasil"
    }
  ]
}
```

5. Adicione o script no arquivo `package.json` para rodar o json-server:
   ```json
   "server": "json-server --watch data/db.json"
   ```

6. Para iniciar o servidor, execute:
   ```bash
   npm run server
   ```

## Utilizando o React Router DOM

O **React Router DOM** é uma biblioteca essencial para gerenciamento de rotas em aplicações React. Ele permite a criação de uma navegação fluida entre diferentes páginas e componentes, além de possibilitar a construção de Single Page Applications (SPAs). 

Para instalar o React Router DOM, utilize o comando:

```bash
npm install react-router-dom
```

Com ele, será possível criar uma navegação organizada entre as páginas do sistema.

## Arquitetura de Pastas

Organizamos o projeto de forma modular para facilitar a escalabilidade e a manutenção do código. Abaixo está a estrutura inicial do projeto:

```
src/
├── components/
├── pages/
│   ├── Fornecedor/
│   ├── Produto/
│   ├── Cliente/
```

### Descrição das Pastas
- **components**: Contém os componentes reutilizáveis, como botões, cabeçalhos e rodapés.
- **pages**: Armazena as páginas principais do sistema.
  - **Fornecedor**: Páginas relacionadas à gestão de fornecedores.
  - **Produto**: Páginas relacionadas à gestão de produtos.
  - **Cliente**: Páginas relacionadas à gestão de clientes.
#   g e r e n c i a d o r _ d e _ p r o d u t o s _ f r o n t  
 