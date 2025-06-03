# ☁️ Weather API App

Este é um aplicativo simples de previsão do tempo que permite buscar informações climáticas de qualquer cidade ao redor do mundo. Ele exibe a temperatura, umidade, velocidade do vento e uma imagem representativa do clima.

## ✨ Funcionalidades

* **Busca de Cidade**: Digite o nome de uma cidade para obter suas informações climáticas.
* **Informações Detalhadas**: Exibe temperatura, umidade e velocidade do vento.
* **Ícone do Clima**: Mostra um ícone visual correspondente às condições climáticas atuais.
* **Tema Dinâmico**: A cor de fundo do cartão de clima muda de acordo com a temperatura.

## 🚀 Demonstração

Aqui está uma prévia de como o aplicativo se parece:

![Demonstração do Aplicativo de Clima](assets/image_b2fcb8.png)

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estrutura da página.
* **CSS3**: Estilização e responsividade.
* **JavaScript**: Lógica de busca de dados e manipulação do DOM.
* **Font Awesome**: Ícones utilizados no design.
* **WeatherAPI.com**: API utilizada para obter os dados climáticos.

## ⚙️ Como Executar o Projeto

Siga estes passos para configurar e executar o projeto em seu ambiente de desenvolvimento.

### Pré-requisitos

* Um editor de código, como o [VS Code](https://code.visualstudio.com/).
* Uma conexão com a internet para buscar os dados da API.
* Uma chave de API da WeatherAPI.com (gratuita).

### 1. Obtenha sua Chave de API

1.  Acesse o site da [WeatherAPI.com](https://www.weatherapi.com/).
2.  Crie uma conta gratuita.
3.  Após o login, sua chave de API estará disponível no seu painel. Copie-a.

### 2. Configure o Projeto no VS Code

1.  **Crie os arquivos:**
    * Crie uma pasta para o seu projeto (ex: `weather-app`).
    * Dentro dessa pasta, crie os seguintes arquivos:
        * `index.html`
        * `style.css`
        * `weatherapi.js` (ou o nome que você preferir para o seu JavaScript)
        * `image_cd4771.png` (coloque a imagem que você me forneceu dentro da pasta do projeto)

2.  **Cole o código:**

    * **`index.html`**: Cole o código HTML fornecido.
    * **`style.css`**: Cole o código CSS fornecido.
    * **`weatherapi.js`**: Cole o código JavaScript fornecido.

3.  **Insira sua Chave de API no JavaScript:**
    * Abra o arquivo `weatherapi.js`.
    * Encontre a linha que define a chave da API:
        ```javascript
        const key = 'd1ae50a228974572895183722252905';
        ```
    * Substitua `'d1ae50a228974572895183722252905'` pela sua chave de API da WeatherAPI.com que você obteve no passo 1.

### 3. Instale a Extensão "Live Server" (Recomendado)

Para facilitar o desenvolvimento e visualizar as alterações em tempo real, recomendamos a instalação da extensão "Live Server" no VS Code:

1.  Abra o VS Code.
2.  Vá para a aba de Extensões (ícone de blocos no lado esquerdo ou `Ctrl+Shift+X`).
3.  Pesquise por "Live Server" e instale a extensão por Ritwick Dey.

### 4. Execute o Aplicativo

1.  Com a extensão "Live Server" instalada, abra o arquivo `index.html` no VS Code.
2.  Clique com o botão direito do mouse em `index.html` no explorador de arquivos do VS Code.
3.  Selecione a opção "Open with Live Server".

Isso abrirá o aplicativo em seu navegador padrão. Agora você pode digitar o nome de uma cidade no campo de busca e pressionar `Enter` para ver as informações climáticas.
