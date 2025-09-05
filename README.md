#Projeto Integrador - Proposta de Sistema Orientado a Objetos – Segunda Entrega

##Protótipos da interface do sistema:

Cadastro de Pessoa Física:
<img width="1357" height="841" alt="image" src="https://github.com/user-attachments/assets/e336ad6c-f7a5-49ab-b0cd-4a3721c4c6c9" />

Cadastro de Pessoa Jurídica
<img width="1359" height="836" alt="image" src="https://github.com/user-attachments/assets/8595446f-64e4-4eeb-a3b4-04342aec21c1" />

Cadastro de Professor
<img width="1343" height="800" alt="image" src="https://github.com/user-attachments/assets/c9f1cba3-d7d8-45c6-9e95-daf8019909d3" />
<img width="1361" height="765" alt="image" src="https://github.com/user-attachments/assets/76a567a8-c308-4d0e-b448-71c34e7321eb" />

Cadastro de Aluno
<img width="1357" height="794" alt="image" src="https://github.com/user-attachments/assets/692dde29-21f8-4987-afc5-3aef549f72d4" />
<img width="1359" height="448" alt="image" src="https://github.com/user-attachments/assets/c0200bac-3aef-4d3d-aa05-f36d8b07778b" />

Cadastro de Fornecedor - Pessoa Física
<img width="1359" height="812" alt="image" src="https://github.com/user-attachments/assets/73ff4f43-321c-4651-9446-dba15106936f" />
<img width="1361" height="559" alt="image" src="https://github.com/user-attachments/assets/15e7578e-8aa1-46f4-818c-869476372f0f" />

Cadastro de Fornecedor - Pessoa Jurídica
<img width="1358" height="815" alt="image" src="https://github.com/user-attachments/assets/14f54d59-5334-43c7-871d-e413ef9b08e2" />
<img width="1360" height="571" alt="image" src="https://github.com/user-attachments/assets/240a145e-4d99-4dd1-bda7-7fc22b6bfc89" />


## Visão Geral do Projeto

Este projeto consiste na modelagem e prototipação de um Sistema de Gestão Universitária. Na primeira fase, o grupo desenvolveu a modelagem orientada a objetos usando a Linguagem Unificada de Modelagem (UML), criando os diagramas de Casos de Uso e de Classes. A segunda fase se concentra na prototipação das interfaces do sistema e na organização da documentação no GitHub.

## Primeira Entrega: Modelagem UML

### Diagrama de Casos de Uso

O diagrama de casos de uso foi projetado para atender às necessidades de cadastro e gerenciamento de diferentes tipos de pessoas que interagem com a universidade. Os principais atores são o **Administrador** e o **Operador**.

**Casos de Uso Principais:**
- **Cadastro de Pessoa Física:** O sistema processa e valida dados como nome, CPF, RG, data de nascimento, endereço, telefone e e-mail.
- **Cadastro de Pessoa Jurídica:** Valida o CNPJ e garante que a pessoa jurídica fique disponível para contratos e parcerias.
- **Cadastro de Professor:** Especialização do cadastro de pessoa física, com campos adicionais para informações acadêmicas e funcionais.
- **Cadastro de Fornecedor:** Flexível para se adaptar tanto a pessoas físicas quanto jurídicas, com campos específicos para tipo, área de atuação e dados bancários.
- **Cadastro de Aluno:** Focado no processo de ingresso do aluno, com campos para curso, ano/semestre e forma de ingresso.

**Imagem do Diagrama de Casos de Uso:**
### Diagrama de Classes e Relacionamentos

O modelo de classes foi desenvolvido com conceitos de orientação a objetos, utilizando herança, associações e composições.

- A classe abstrata **Pessoa** serve como base.
- **PessoaFisica** e **PessoaJuridica** herdam de **Pessoa**.
- **Professor** e **Aluno** herdam de **PessoaFisica**.
- **Fornecedor** pode herdar tanto de **PessoaFisica** quanto de **PessoaJuridica**.
- As classes **Curso** e **Endereco** complementam o modelo.

**Relacionamentos:**
- **Composição:** `Pessoa` possui um `Endereco`.
- **Associação:**
    - `Professor` está associado a `Curso` (coordenação).
    - `Aluno` está associado a `Curso` (matrícula).
    - `Fornecedor` está associado a `Curso` (fornecimento).

**Imagem do Diagrama de Classes:**
---

## Segunda Entrega: Prototipação e Repositório

### Protótipos das Interfaces (Figma/Miro)

Os protótipos desenvolvidos refletem a modelagem da primeira fase, com interfaces visuais para cada jornada de cadastro.

**Link para os Protótipos: https://www.figma.com/design/EQiNijProiHCUElSsTvH76/Untitled?node-id=0-1&t=m3m83eJNrpicDyto-1
