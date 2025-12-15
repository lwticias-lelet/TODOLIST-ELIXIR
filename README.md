# Elixir Todo List

## 📌 Informações do Aluno
- **Nome do Aluno:** Leticia Delfino de Araujo  
- **Professor:** Sergio Costa
- **Curso:** Engenharia da Computação  
- **Universidade:** Universidade Federal do Maranhão (UFMA)  

## 🔗 Link do Tutorial
- [Tutorial Original no Notion] https://profsergiocosta.notion.site/Como-Criar-um-App-Todo-List-com-Elixir-e-LiveView-do-Zero-2a8cce97509380eba53fc82bbeb08435

## 📝 Descrição do Projeto
Este projeto é uma **Lista de Tarefas (Todo List)** desenvolvida com **Elixir**, utilizando **Phoenix Framework** e **LiveView** para a interface dinâmica.  
O projeto integra persistência de dados com **Ecto** e **SQLite**, e utiliza **TailwindCSS** junto com **daisyUI** para estilização.  

Funcionalidades principais:
- Adicionar novas tarefas.
- Marcar tarefas como concluídas.
- Deletar tarefas.
- Interface interativa sem reload de página (via LiveView).

## ⚙️ Tecnologias Utilizadas
- **Elixir 1.15+**
- **Phoenix 1.8+**
- **LiveView**
- **Ecto + SQLite**
- **TailwindCSS + daisyUI**


## 🚀 Como Rodar

### Pré-requisitos
- **Elixir** (versão 1.15 ou superior)   eu usei versão 17.2 
- **Erlang/OTP** compatível com o Elixir  - eu usei a versão 26.2.2
- **Node.js** (para TailwindCSS e esbuild)  
- **Git** (opcional, para clonar o repositório)

### Passos para executar

1. Clone o repositório:
```bash
git clone <URL_DO_REPOSITORIO>
cd elixir_todo_list
Instale as dependências:

mix deps.get


Prepare o banco de dados:

mix ecto.create
mix ecto.migrate


Instale dependências de assets:

mix assets.setup
mix assets.build


Inicie o servidor Phoenix:

mix phx.server


Abra o navegador e acesse:

http://localhost:4000

Para mudar o tema ou cores do projeto, altere as classes do TailwindCSS ou configure o daisyUI em tailwind.config.js.

📂 Estrutura do Projeto
elixir_todo_list/
├─ lib/elixir_todo_list_web/live/todo_live.ex  # LiveView da lista de tarefas
├─ lib/elixir_todo_list/tasks/task.ex         # Schema Task
├─ priv/repo/migrations/                       # Migrações Ecto
├─ assets/css/app.css                           # CSS (Tailwind)
├─ config/config.exs                            # Configuração geral
├─ mix.exs                                      # Configuração do projeto e dependências
└─ README.md                                    # Documentação
💡 Observações

saiba maisss

* Official website: https://www.phoenixframework.org/
* Guides: https://hexdocs.pm/phoenix/overview.html
* Docs: https://hexdocs.pm/phoenix
* Forum: https://elixirforum.com/c/phoenix-forum
* Source: https://github.com/phoenixframework/phoenix
