# ToDoList
📝 ToDo App — Lista de Tarefas Simples com Kivy

Este projeto é um aplicativo de lista de tarefas desenvolvido em Python utilizando o framework Kivy.
Ele permite adicionar, marcar como concluída e salvar tarefas localmente em um arquivo tasks.json.

📂 Estrutura do Projeto
📁 projeto-todo/
│── main.py          # Arquivo principal com a lógica do app
│── todo.kv          # Interface visual do Kivy
│── tasks.json       # Armazena as tarefas
│── README.md        # Documentação

🛠️ Tecnologias Utilizadas

Python 3.8+

Kivy 2.3.0+

JSON (para armazenamento local)

⚙️ Como Instalar e Rodar
1. Clone o repositório
git clone https://github.com/usuario/projeto-todo.git
cd projeto-todo

2. Crie um ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows

3. Instale as dependências
pip install kivy

4. Execute o aplicativo
python main.py

📱 Como Usar o Aplicativo

✏️ Digite uma tarefa no campo de texto.

➕ Clique em “Add” para adicioná-la à lista.

✅ Marque ou desmarque a caixa de seleção para indicar se a tarefa foi concluída.

💾 As tarefas são salvas automaticamente no arquivo tasks.json.

🔁 Ao reabrir o app, suas tarefas continuam lá.

🗃️ Estrutura do Arquivo tasks.json

Exemplo:

[
    {
        "text": "Estudar Kivy",
        "completed": false
    },
    {
        "text": "Fazer exercícios",
        "completed": true
    }
]


text: Nome da tarefa

completed: true se a tarefa estiver concluída, false caso contrário.

🎨 Interface (todo.kv)

A interface foi construída com o arquivo .kv:

Título “To Do”

Campo de entrada e botão “Add”

Lista dinâmica com CheckBox + Label

Layout responsivo (414 x 736 px por padrão)

🧹 Possíveis Melhorias Futuras

🗑️ Botão para excluir tarefas

🕒 Ordenação por tarefas concluídas ou pendentes

☁️ Integração com banco de dados online

📱 Geração de APK com Buildozer

🧑‍💻 Autor: Matheus da C. Fernandes

Feito usando Python e Kivy.
📬 Para dúvidas ou sugestões: matheuscosta30112020@gmail.com

📜 Licença

Este projeto é de uso livre para fins educacionais.
