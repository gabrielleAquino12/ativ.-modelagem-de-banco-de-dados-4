# ativ.-modelagem-de-banco-de-dados-4
Scripts SQL da experiência prática 4

 🐱 Sistema de Adoção de Gatos – ONG resgate de gatos

Este repositório contém o projeto desenvolvido para a disciplina de Modelagem de Banco de Dados, abordando modelagem conceitual, lógica e física de um sistema de adoção de gatos.

📌 Objetivo do Sistema
O sistema tem como finalidade organizar e gerenciar:
- Cadastro de gatos
- Cadastro de adotantes
- Registros de adoções
- Relacionamentos entre as entidades

 Tabelas do Banco

Adotante
| Campo | Tipo | Descrição |
|------|------|-----------|
| idAdotante | INT | Identificador |
| nome | VARCHAR | Nome completo |
| cpf | VARCHAR | CPF do adotante |
| telefone | VARCHAR | Contato |
| endereco | VARCHAR | Endereço |

Gato
| Campo | Tipo | Descrição |
|------|------|-----------|
| idGato | INT | Identificador |
| nome | VARCHAR | Nome do gato |
| idade | INT | Idade aproximada |
| cor | VARCHAR | Cor do gato |
| sexo | ENUM | Macho/Fêmea |
| castrado | BOOLEAN | Castrado ou não |
| vacinado | BOOLEAN | Vacinado ou não |

Adoção
| Campo | Tipo | Descrição |
|------|------|-----------|
| idAdocao | INT | Identificador |
| dataAdocao | DATE | Data da adoção |
| idAdotante | INT | FK Adotante |
| idGato | INT | FK Gato |
| status | VARCHAR | Status da adoção |

Como executar o SQL?
1. Acesse o **dB Fiddle**  
2. Escolha "MySQL 8"  
3. Cole o conteúdo do arquivo `banco_de_dados.sql`  
4. Clique em **Build Schema**  
5. Execute consultas normalmente

---

💬📞 Contato
Caso precise de ajuda, estou à disposição! 

site testado: https://www.db-fiddle.com/

Gabrielle Aquino.
 
