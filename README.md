# Projeto Primeira Venda no Orgânico

Este projeto é uma aplicação web que ensina estratégias para conseguir a primeira venda de forma 100% orgânica, utilizando plataformas como Instagram e TikTok.

## Estrutura do Projeto

- **app.py**: Ponto de entrada da aplicação, onde o servidor web é configurado e as rotas são definidas.
- **requirements.txt**: Lista de dependências do projeto. Utilize este arquivo para instalar as bibliotecas necessárias com o gerenciador de pacotes.
- **.gitignore**: Arquivo que especifica quais arquivos ou diretórios devem ser ignorados pelo Git.
- **templates/**: Diretório que contém os arquivos HTML.
  - **base.html**: Modelo base para as páginas HTML, contendo a estrutura comum da aplicação.
  - **index.html**: Página inicial da aplicação, que herda do `base.html`.
- **static/**: Diretório que contém os arquivos estáticos da aplicação.
  - **css/**: Contém os estilos CSS.
    - **styles.css**: Estilos para a aplicação.
  - **js/**: Contém o código JavaScript.
    - **main.js**: Funcionalidades dinâmicas da aplicação.
  - **fonts/**: Diretório para fontes personalizadas.
  - **images/**: Diretório para imagens utilizadas na aplicação.

## Instalação

1. Clone o repositório:
   ```
   git clone <URL do repositório>
   ```
2. Navegue até o diretório do projeto:
   ```
   cd primeira-venda-organico
   ```
3. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```

## Uso

Para iniciar a aplicação, execute o seguinte comando:
```
python app.py
```
A aplicação estará disponível em `http://localhost:5000`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.