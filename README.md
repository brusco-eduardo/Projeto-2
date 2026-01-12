# Projeto-2 - Organizador para IR
Projeto em Excel para organizar e consolidar informações da declaração do Imposto de Renda. Agregador com menus de navegação, validações automáticas e links rápidos para facilitar o preenchimento e a conferência dos dados. Projeto realizado no Santander — Excel com Inteligência Artificial (2º semestre, DIO).
[README1.md](https://github.com/user-attachments/files/24567033/README1.md)

> Ferramenta desenvolvida em planilha de Excel para organizar declaração de imposto de renda.

Índice
- [Sobre](#sobre)
- [Como funciona](#como-funciona)
- [Funcionalidades](#funcionalidades)
- [Estrutura das abas](#estrutura-das-abas)
- [Como usar](#como-usar)
- [Contato](#contato)

## Sobre
Este projeto tem como objetivo criar uma ferramenta em Excel que ajude a organizar e reunir informações essenciais para a declaração do Imposto de Renda. A proposta é construir um agregador de dados no qual o usuário possa controlar suas entradas de maneira eficiente e validada, com menus de navegação, validações automáticas e funcionalidades extras, como links rápidos.

## Como funciona
A ferramenta funciona como um agregador de informações e gerador de resumos para a declaração do Imposto de Renda, totalmente construída dentro do Excel. Seu funcionamento depende do usuário preencher as informações solicitadas, que ao final se tornam uma ficha resumo de sua declaração.

## Funcionalidades
- Agregador de Informações.
- Visão agregada dos informes bancários.
- Visão agregada das receitas do ano.
- Menu de navegação.

## Estrutura das abas
- `Titular`: coleta as informações básicas para cadastro do usuário, como nome, endereço, etc.
- `Informes`: aba que agrega anexos e resumos dos informes bancários.
- `Notas`: destinada a registro dos recebimentos, por holerite, CNPJ, ou Freelance.
- `Tabelas` (oculta): base com lista de bancos e seus códigos.

## Como usar
1. Abrir o arquivo
   - Abra a planilha no Microsoft Excel e, se solicitado, clique em "Habilitar Edição".

2. Preencher os dados do titular
   - Vá para a aba `Titular` e complete as informações básicas (nome, CPF, endereço, dependentes, contato, etc.). Esses dados são usados em relatórios e validações.

3. Inserir/colar os informes bancários
   - Na aba `Informes`, preencha as celulas com as informações encontradas em seus informes bancários e anexe uma cópia na célula indicada.
   - Use os menus suspensos para selecionar o banco/categoria; .

4. Registrar receitas
   - Na aba `Notas`, registre todos os recebimentos, informando a Data do recebimento, a categoria (Holerite, CNPJ, Freelance) e valor.

5. Navegar e utilizar o menu
   - Use o menu de navegação (hiperlinks ou botões presentes na planilha) para saltar rapidamente entre seções: Titular, Informes, Notas, Resumo/Checklist (se disponível) e Docs.

6. Boas práticas antes de finalizar
   - Salve uma cópia do arquivo (ex.: nome_do_arquivo_v1.xlsx) antes de fazer alterações massivas.
   - Remova ou anonimise dados sensíveis antes de compartilhar publicamente.

## Contato
- Autor: Eduardo Migliorini Brusco 
- Email: <eduardo.brusco@unesp.br>
