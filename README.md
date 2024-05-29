# Pokédex
Link: https://lucasyuki01.github.io/Pokedex/

Uma aplicação web interativa que permite aos usuários procurar Pokémon pelo nome ou número e visualizar suas estatísticas em um gráfico de radar.

## Índice

- [Visão Geral](#visão-geral)
- [Demonstração](#demonstração)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral

Esta Pokédex foi desenvolvida utilizando HTML, CSS e JavaScript. A aplicação consome a [PokeAPI](https://pokeapi.co/) para obter dados sobre os Pokémon e exibe esses dados de forma visualmente atraente.

## Demonstração

Você pode acessar a Pokédex online [aqui](#).

## Funcionalidades

- Pesquisar Pokémon pelo nome ou número.
- Navegar pelos Pokémon usando botões de próximo e anterior.
- Exibir uma imagem animada do Pokémon.
- Mostrar nome, número, tipo, peso e altura do Pokémon.
- Visualizar as estatísticas do Pokémon em um gráfico de radar.

## Instalação

Para executar o projeto localmente, siga estas etapas:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/pokedex.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd pokedex
   ```

3. Abra o arquivo `index.html` em seu navegador:
   ```bash
   open index.html
   ```

## Uso

1. Digite o nome ou número de um Pokémon na barra de pesquisa e pressione Enter.
2. Navegue pelos Pokémon utilizando os botões "Prev" e "Next".
3. Veja a imagem do Pokémon, nome, número, tipo, peso, altura e suas estatísticas no gráfico de radar.

## Estrutura do Projeto

```
pokedex/
├── css/
│   └── style.css
├── images/
│   ├── favicon-16x16.png
│   ├── pokedex-direita.png
│   └── pokedex-esquerda.png
├── js/
│   └── script.js
├── index.html
└── README.md
```

- `css/style.css`: Contém os estilos para a Pokédex.
- `images/`: Contém as imagens usadas no projeto.
- `js/script.js`: Contém o código JavaScript que faz chamadas à PokeAPI e manipula o DOM.
- `index.html`: A estrutura HTML da Pokédex.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

1. Faça um fork do projeto.
2. Crie uma nova branch:
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. Faça suas alterações e commit:
   ```bash
   git commit -m 'Adiciona nova funcionalidade'
   ```
4. Faça push para a branch:
   ```bash
   git push origin feature/nova-funcionalidade
   ```
5. Abra um pull request.
