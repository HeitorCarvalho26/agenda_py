# Agenda em Pythom usando Flask

Este projeto foi elaborado para permitir o aprendizado de conceitos como o padrão de projeto MVC (Model-View-COntroller), framework Flask e seus componentes variáveis de ambiente, paradigma de programação orientada a objetos e reforço de fundamentos da linguagem de programação python.

para implantar este projeto localmente, siga os seguintes passo:

1. Faça um fork desse repositório, clicando no botão `Fork`

2. Clone seu repositorio localmente:

~~~bash
git clone  <url_seu_repositorio>
~~~

3. Abra o projeto utilizando seu IDE preferido

4. Crie, preferencialmete, um ambiente virtual utilizando a versão do Pythom >3.12.10

~~~bash
pytohm -m venv .venv
~~~

5. Ative seu ambiente virtual.

    No bash:

    ~~~bash
    source .venv/scripts/activete
    ~~~

    No PowerShell:
    ~~~powershell
    .\.venv\Scripts\Activate.ps1

6. Instale todas as dependências constantes no `requirements.txt`:

~~~python
pip install -r requirements.txt
~~~

7. Copie o arquivo `.env.exemple` cole na raiz do projeto e renomeie esse arquivo para `.env.`

8. Edite o arquivo `.env` para definir o caminho do seu banco de dados na constatnte `DATABASE`. Exemplo

~~~env
DATABASE='./data/meubanco.db'
~~~

9. Rode da aplicação no python utilizando o comando:

~~~bash
flask run
~~~

10. Acesse a aplicação no endereço e porta indicados no terminal. Exemplo:
`http://127.0.0.1:5000`