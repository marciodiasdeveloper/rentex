# Express NodeJS (Rentex Project) (Aluguel de carros)

## Cadastro de carro

**Requisitos Funcionais**
- Deve ser possível cadastrar um novo carro.
- Deve ser possível listar todas as categorias.

**Requisitos Não Funcionais**

**Regras de negócio**
- Não deve ser possível cadastrar um carro com uma placa já existente.
- Não deve ser possível alterar a placa de um carro já cadastrado.
- O carro deve ser cadastrado, por padrão, com disponibilidade.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

## Listagem de carros

**Requisitos Funcionais**
- Deve ser possível listar todos os carros disponíveis.
- Deve ser possível listar todos os carros disponíveis pelo nome da categoria.
- Deve ser possível listar todos os carros disponíveis pelo nome da marca.
- Deve ser possível listar todos os carros disponíveis pelo nome do carro.

**Requisitos Não Funcionais**

**Regras de negócio**
- O usuário não precisa estar logado no sistema.

# Cadastro de especificação no carro.

**Requisitos Funcionais**
- Deve ser possível cadastrar uma especificação para um carro.
- Deve ser possível listar todas as especificaçòes.
- Deve ser possível listar todos os carros.

**Regras de negócio**
- Não deve ser possível cadastrar uma especificação para um carro não cadastra
do.
- Não deve ser possível cadastrar uma especificação já existente para um mesmo carro.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

## Cadastro de imagens do carro.


**Requisitos Funcionais**
- Deve ser possível cadastrar a imagem do carro.
- Deve ser possível listar todos os carros.

**Requisitos Não Funcionais**
- Utilizar o multer para upload de arquivos.

**Regras de negócio**
- O usuário deve poder cadastrar 


## Aluguel

**Requisitos Funcionais**
- Deve ser possível cadastrar um aluguel.


**Regras de negócio**
- O aluguel deve ter duração mínima de 24 horas.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.