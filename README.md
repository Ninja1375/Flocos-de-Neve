# Flocos de Neve

## Descrição

Este é um simples efeito visual de flocos de neve caindo sobre a página, utilizando HTML, CSS e JavaScript. O projeto foi criado para simular flocos de neve flutuando pela tela, criando um efeito visual encantador para websites durante o inverno ou para dar um toque festivo.

## Funcionalidades

- **Efeito de flocos de neve**: Flocos de neve caem da parte superior da tela com variações de tamanhos e velocidades.
- **Responsivo**: O efeito se adapta ao tamanho da janela do navegador, garantindo uma experiência consistente em diferentes dispositivos.
- **Text Shadow**: Caso o navegador suporte, é aplicado um efeito de sombra no texto dos flocos de neve, tornando-os ainda mais visíveis.

## Tecnologias Utilizadas

- **HTML**: Estrutura básica da página.
- **CSS**: Estilização do fundo da página e dos flocos de neve.
- **JavaScript**: Lógica para gerar os flocos de neve e movê-los pela tela. A biblioteca jQuery foi utilizada para facilitar manipulações DOM e animações.

## Como Usar

1. Clone este repositório para o seu ambiente local ou baixe os arquivos.
2. Abra o arquivo `index.html` em um navegador para ver o efeito em ação.
3. O projeto também pode ser integrado a outros sites para adicionar o efeito de flocos de neve facilmente.

## Como Funciona

### HTML

O arquivo `index.html` configura a estrutura básica da página e inclui os arquivos CSS e JavaScript necessários para o funcionamento do efeito. A tag `<script>` carrega a biblioteca jQuery para facilitar a manipulação dos elementos DOM.

### CSS

O arquivo `style.css` define a cor de fundo da página e outras configurações visuais, como o tamanho e o posicionamento dos flocos de neve.

```css
body {
    background: #e80707;
}
```

### javaScript

O arquivo ```script.js``` contém a lógica que gera os flocos de neve. Cada floco é um elemento ```span``` com um ícone de floco de neve e estilos aleatórios, como tamanho e velocidade. A função ```move()``` move os flocos pela tela, e novos flocos são gerados conforme os antigos saem da tela.
