[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IDEzcQ6G)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23810443)
# :checkered_flag:Store da Manicure

Um site para vendas de produtos de beleza e cursos do mesmo segmento

## :technologist: Membros da equipe

Matrícula, nome e curso dos participantes.
540739 - João Victor Feitosa Cavalcante - Redes de Computadores
539402 - David Silva  Fernandes de Oliveira - Engenharia de Computação

## :bulb: Objetivo Geral
O site vai impulsionar e facilitar as vendas do nosso cliente, facilitando o acesso do usúario ao produto desejado

## :eyes: Público-Alvo
Profissionais do setor de beleza (maquiadores, cabeleireiros, esteticistas), entusiastas de cuidados pessoais, e pessoas que buscam iniciar ou se especializar no mercado da beleza através de cursos online.
## :star2: Impacto Esperado

Aumentar o faturamento e a presença digital da loja, permitindo que clientes de diversas regiões tenham acesso aos produtos. Além disso, agregar valor ao negócio fidelizando o consumidor, que poderá comprar os cosméticos e aprender a utilizá-los profissionalmente no mesmo ambiente.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Visitante (Usuário não logado): Pode explorar o catálogo de produtos, visualizar detalhes dos cursos disponíveis e pesquisar itens no site.

Cliente / Aluno (Usuário logado): Pode adicionar itens ao carrinho, realizar compras, rastrear pedidos e acessar a "Área do Aluno" para assistir às aulas dos cursos adquiridos.

Administrador: Possui acesso total ao painel de controle para gerenciar estoque, adicionar ou remover produtos e cursos, moderar usuários e visualizar relatórios de vendas.
> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

Acessíveis a todos:

Vitrine virtual com listagem e filtragem de produtos e cursos por categorias.

Barra de busca integrada.

Página de detalhes com descrição, preço e avaliações.

Restritas a usuários logados:

Carrinho de compras e checkout de pagamento.

Histórico de pedidos.

Restritas ao Administrador:

Painel (Dashboard) para gestão (CRUD) de produtos e cursos.

Controle de estoque e status de pedidos.

## :spiral_calendar: Entidades ou tabelas do sistema

Usuário (Dados de clientes e administradores)

Produto (Informações dos cosméticos, estoque, preço)

Curso (Informações do curso, módulos, carga horária)

Categoria (Para agrupar produtos e cursos, ex: "Maquiagem", "Skincare", "Cursos Profissionalizantes")

Pedido (Registro das transações de compras, status de pagamento)


----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

HTML5

CSS3 (Vanilla)

JavaScript (Vanilla)

**Backend:**

Strapi

SQLite

Autenticação via JWT nativa do Strapi.

## :shipit: Operações implementadas para cada entidade da aplicação

| Entidade | Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Curso | X |  X  |  X  | X |
| Aula | X |  X  |  X  | X |
| Produto | X |  X  |  X  | X |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| POST | /api/auth/local |
| POST | /api/auth/local/register |
| GET | /api/cursos |
| POST | /api/cursos |
| PUT | /api/cursos/:id |
| DELETE | /api/cursos/:id |
| GET | /api/aulas |
| POST | /api/aulas |
| PUT | /api/aulas/:id |
| DELETE | /api/aulas/:id |
| GET | /api/produtos |
| POST | /api/produtos |
| PUT | /api/produtos/:id |
| DELETE | /api/produtos/:id |

