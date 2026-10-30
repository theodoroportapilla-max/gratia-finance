# Requisitos do Sistema — Gratia Finance

## 1. Introdução

Este documento apresenta os requisitos funcionais e não funcionais do Gratia Finance, uma plataforma de gerenciamento financeiro pessoal.

O objetivo é definir as funcionalidades e características técnicas necessárias para o desenvolvimento do sistema.

## 2. Requisitos Funcionais (RF)

- **RF01:** Permitir o cadastro de usuários.
- **RF02:** Permitir o login e logout.
- **RF03:** Permitir a recuperação de senha.
- **RF04:** Exibir um dashboard com resumo financeiro.
- **RF05:** Permitir cadastrar receitas.
- **RF06:** Permitir cadastrar despesas.
- **RF07:** Permitir editar e excluir movimentações.
- **RF08:** Permitir cadastrar e gerenciar contas financeiras.
- **RF09:** Permitir criar e organizar categorias.
- **RF10:** Exibir o histórico de movimentações.
- **RF11:** Permitir filtrar movimentações por período, categoria e tipo.
- **RF12:** Exibir gráficos e relatórios financeiros.
- **RF13:** Permitir criar metas financeiras.
- **RF14:** Permitir acompanhar o progresso das metas.
- **RF15:** Permitir definir orçamentos por categoria.
- **RF16:** Exibir o saldo e os valores totais de receitas e despesas.

## 3. Requisitos Não Funcionais (RNF)

- **RNF01:** O sistema deverá possuir uma interface responsiva.
- **RNF02:** As senhas deverão ser armazenadas de forma segura.
- **RNF03:** O sistema deverá utilizar HTTPS em produção.
- **RNF04:** Os dados financeiros deverão ser acessíveis somente por usuários autorizados.
- **RNF05:** O banco de dados deverá utilizar MySQL.
- **RNF06:** O backend deverá ser desenvolvido em PHP.
- **RNF07:** As consultas ao banco deverão utilizar instruções preparadas.
- **RNF08:** O sistema deverá validar os dados enviados pelos usuários.
- **RNF09:** A interface deverá ser intuitiva e de fácil utilização.
- **RNF10:** A arquitetura deverá permitir futuras integrações com aplicativos mobile por meio de API REST.
- **RNF11:** O código deverá ser organizado para facilitar manutenção e expansão.

## 4. Observações

Os requisitos poderão ser revisados e ampliados conforme o desenvolvimento do Gratia Finance evoluir.

As funcionalidades serão implementadas gradualmente, priorizando inicialmente a plataforma Web.
