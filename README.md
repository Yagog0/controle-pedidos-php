# Controle de pedidos | PHP
Projeto de aprendizado desenvolvido durante meu estágio na Energy Simple, com uma primeira versão de gerenciamento de pedidos e uma segunda proposta de interface com jQuery EasyUI.

## Tecnologias
- PHP e PDO
- Banco de dados relacional
- HTML, CSS e JavaScript
- jQuery EasyUI no protótipo da V2

## Versões
| Versão | Localização | Conteúdo |
| --- | --- | --- |
| V1 | [gere_pedidos_v1](gere_pedidos_v1/) | Cadastro e edição de clientes e itens, gerenciamento de pedidos, itens por pedido e cálculo de totais |
| Protótipo V2 | Arquivos PHP na raiz | Menu lateral, tela de entrada e estrutura inicial de interface com EasyUI |

A V2 está em desenvolvimento: algumas telas contêm apenas a estrutura inicial. A presença da tela de entrada não representa uma autenticação concluída.

## Conhecendo o projeto
1. Comece pela pasta `gere_pedidos_v1/` para conhecer o CRUD.
2. Confira a configuração em `gere_pedidos_v1/conexao.php` e adapte-a ao seu ambiente local.
3. Prepare um servidor com suporte a PHP, PDO e ao banco configurado. O banco deve conter as tabelas e os campos usados nas consultas.
4. Para explorar o protótipo V2, disponibilize os arquivos do EasyUI nos caminhos `easyui/` referenciados pelas páginas. Há referências a endpoints que precisam ser implementados ou configurados.

## Evolução
| Data | Entrega | Referência |
| --- | --- | --- |
| 06/03/2026 | Primeira versão do CRUD | [c60eb3e](https://github.com/Yagog0/php-crud-teste-energy-simple/commit/c60eb3e137ea1b7215785564197da77b95d39833) |
| 06/03/2026 | Inclusão do documento do exercício | [3fef98b](https://github.com/Yagog0/php-crud-teste-energy-simple/commit/3fef98b676620ef91aa2c9bf74b7cfc2df59e1b8) |
| 10/03/2026 | Protótipo de interface com EasyUI | [c8f64a9](https://github.com/Yagog0/php-crud-teste-energy-simple/commit/c8f64a901caea8eac5681a80b1509cb7ed1ee4c3) |

## Autor
Desenvolvido por [Yago](https://github.com/Yagog0).
