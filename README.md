# Aplicação de tradução com Flask e Azure

Esta é uma aplicação web simples em Flask que utiliza o serviço de tradução do Azure para traduzir textos de um idioma para outro. A aplicação permite que os usuários insiram um texto em um idioma de origem e selecionem um idioma de destino para a tradução. A tradução é feita usando o serviço de tradução do Azure e o resultado é exibido na página da web.

## Pré-requisitos
Antes de executar a aplicação, você precisará das seguintes ferramentas e recursos:

- Python 3.x instalado em seu sistema
- Uma conta do Azure com as chaves de API do serviço de tradução
- Flask e outras dependências Python instaladas (veja o arquivo requirements.txt)

## Como executar a aplicação

Clone este repositório para o seu sistema local usando o comando git clone.
Crie um ambiente virtual para a aplicação usando o comando python -m venv venv.
Ative o ambiente virtual usando o comando venv\Scripts\activate (Windows) ou source venv/bin/activate (Linux/Mac).
Instale as dependências Python usando o comando pip install -r requirements.txt.
Configure as variáveis de ambiente com as chaves de API do serviço de tradução. Você pode fazer isso exportando as variáveis de ambiente em um terminal ou criando um arquivo .env na raiz do projeto com as seguintes variáveis:

~~~
KEY=Insira a chave gerada no azure
ENDPOINT=https://api.cognitive.microsofttranslator.com/
LOCATION=brazilsouth
~~~
Execute a aplicação usando o comando flask run.
Abra um navegador e acesse http://localhost:5000 para acessar a aplicação.
