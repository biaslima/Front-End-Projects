# CitySky

CitySky é uma site que permite ao usuário consultar informações meteorológicas de qualquer cidade do mundo. Utilizando a API do OpenWeatherMap, o site exibe dados de temperatura, descrição do tempo, umidade e velocidade do vento.

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte forma:

- **index.html**: O arquivo HTML principal da aplicação.
- **css/styles.css**: Contém os estilos CSS aplicados no site.
- **js/scripts.js**: Contém o script JavaScript responsável por fazer requisições à API do OpenWeatherMap e manipular o DOM.
- **archives/**: Pasta com as imagens usadas na aplicação, como o logo, ícone do tempo e imagem de fundo.

## Funcionalidades Implementadas

- **Busca de Cidade**: O usuário pode digitar o nome de uma cidade para obter informações meteorológicas.
- **Exibição de Dados Meteorológicos**: Mostra a temperatura, descrição do tempo, umidade e velocidade do vento da cidade buscada.
- **Interface Responsiva**: A aplicação possui uma interface adaptável para diferentes tamanhos de tela.
- **Alerta de Erro**: Exibe uma mensagem de alerta se a cidade não for encontrada.

## Instruções para Executar o Projeto

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/biaslima/Front-End-Projects/tree/19eb25e5a1fd2d01b76ffe587e817761aeb7a9ba/CitySky
    cd CitySky
    ```

2. **Abra o arquivo `index.html` no seu navegador**:

3. **Digite o nome de uma cidade no campo de busca** e clique no ícone de lupa para ver as informações meteorológicas.

## Bugs Conhecidos e Melhorias Futuras

### Bugs Conhecidos

- **Exibição Inicial**: A div `#cityWeather` é inicialmente oculta, mas permanece visível após a primeira busca, mesmo se houver um erro na próxima busca.

### Melhorias Futuras

- **Localização Atual**: Adicionar funcionalidade para detectar e exibir o clima com base na localização atual do usuário.
- **Suporte a Outras Línguas**: Permitir a escolha de diferentes idiomas para a interface do usuário.

## Tecnologias Utilizadas

- **HTML**: Para a estrutura da página.
- **CSS**: Para a estilização da interface.
- **JavaScript**: Para a lógica da aplicação e interação com a API do OpenWeatherMap.
- **Font Awesome**: Para ícones.
- **Google Fonts**: Para fontes personalizadas.
