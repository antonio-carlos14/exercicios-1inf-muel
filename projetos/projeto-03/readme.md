<div align="center">

# [🥟 Projeto 03 — Salgaderia Tentação](https://github.com/sudosamm/projeto-03-salgaderia-tentacao/tree/main)

### Reproduza uma página a partir do modelo apresentado pelo cliente

`HTML5` • `CSS externo` • `uma página` • `réplica visual` • `teste manual`

</div>

---

## 🏪 O problema

A **Salgaderia Tentação** é uma pequena lanchonete que vende salgados, pizzas individuais, bebidas e porções. Hoje, o cardápio está espalhado em mensagens e fotografias. Isso dificulta a consulta de preços, ingredientes, horários e formas de contato.

A proprietária procurou uma equipe iniciante de desenvolvimento web. Ela já aprovou um modelo visual e agora precisa que a equipe **reproduza esse modelo em HTML e CSS**.

> [!NOTE]
> A empresa, o endereço e os contatos deste projeto são fictícios. O cenário representa um pedido profissional possível.

## 💬 Mensagem da cliente

> Olá! Sou responsável pela Salgaderia Tentação. Quero uma página simples para mostrar nossos produtos, ingredientes, preços, endereço, horários e contato.
>
> Nossa identidade usa vermelho, amarelo, branco e um fundo claro. Já recebemos uma proposta visual e gostaríamos que a página ficasse parecida com os prints enviados.
>
> Não precisamos de pedidos ou pagamentos pelo site. O mais importante é que uma pessoa consiga consultar o cardápio e encontrar as informações da loja sem dificuldade.

## 🎯 Sua missão

Crie **uma única página** para a Salgaderia Tentação. O objetivo não é inventar outro design: sua equipe deverá observar os modelos, identificar as regiões e tentar reproduzi-las com o conteúdo fornecido.

Não é necessário deixar cada pixel exatamente igual. A entrega precisa preservar:

- a ordem das seções;
- as cores principais;
- a diferença visual entre títulos, textos e links;
- os cartões de produtos e informações;
- os espaçamentos que ajudam a separar o conteúdo;
- todos os dados obrigatórios do cardápio.

---

## 🖼️ Modelos aprovados pela cliente

### Abertura da página

![Modelo da abertura da página da Salgaderia Tentação](./imagens/site-modelo-inicio.png)

### Cardápio

![Modelo da seção de cardápio da Salgaderia Tentação](./imagens/site-modelo-cardapio.png)

### Endereço, horários e contato

![Modelo da seção de informações da Salgaderia Tentação](./imagens/site-modelo-informacoes.png)

### Referência em uma tela estreita

![Modelo da abertura da página em uma tela estreita](./imagens/site-modelo-celular.png)

> [!IMPORTANT]
> Os prints são a referência visual do projeto. Observe primeiro as grandes regiões da página e depois cuide dos detalhes.

## 🎨 Referência visual

| Uso | Cor aproximada |
| --- | --- |
| Vermelho principal | `#9f261f` |
| Amarelo de destaque | `#ffc43d` |
| Fundo amarelo claro | `#ffe3a3` |
| Fundo da página | `#fff8ed` |
| Texto principal | `#38251f` |
| Cartões | `#ffffff` |

A fonte do modelo pertence à família `Arial, Helvetica, sans-serif`.

---

## 📋 Requisitos funcionais

### RF01 — Estrutura do projeto

O projeto deve possuir um `index.html` e uma folha externa em `css/estilos.css`.

### RF02 — Cabeçalho

O cabeçalho deve apresentar:

- a frase **Sabor que chama de volta**;
- o nome **Salgaderia Tentação**;
- uma apresentação curta;
- links para **Destaques**, **Cardápio** e **Endereço e contato**.

Os links podem apontar para seções da mesma página usando `id` e `href="#..."`.

### RF03 — Apresentação

A primeira seção deve possuir:

- o título **Uma tentação em cada mordida**;
- um texto curto sobre a lanchonete;
- um link em formato de botão que leve ao cardápio.

### RF04 — Destaques com imagens

Apresente três produtos em destaque:

1. coxinha de frango;
2. pastel de carne;
3. pizza individual.

Cada destaque deve ter imagem, nome e descrição. As imagens devem estar salvas dentro do projeto e possuir `alt` adequado.

> [!WARNING]
> Não utilize imagens geradas por inteligência artificial. Pesquise fotografias reais e registre a origem em `FONTES.md`.

### RF05 — Cardápio completo

O cardápio deve ser dividido em **Salgados**, **Pizzas individuais**, **Bebidas** e **Porções e combos**. Cada item deve apresentar nome, preço e, quando aplicável, ingredientes ou descrição.

### RF06 — Informações da loja

A parte final da página deve mostrar, em blocos separados:

- endereço;
- horários;
- telefone e e-mail.

### RF07 — Rodapé

O rodapé deve repetir o nome da empresa, avisar que o site é demonstrativo e possuir um link para voltar ao início.

### RF08 — Apresentação visual

O CSS deve se aproximar dos prints utilizando **somente os seletores e as propriedades já estudados no [site temático de exemplo](https://github.com/sudosamm/site-tematico-exemplo)**.

Isso inclui:

- cores de texto e fundo;
- família, tamanho, peso e altura de linha da fonte;
- margem e preenchimento;
- largura;
- bordas e cantos arredondados;
- `display: flex`, `flex-wrap` e `gap`;
- `display: inline-block`;
- `:hover` e `:focus` em links;
- classes reutilizáveis.

> [!CAUTION]
> Não é necessário pesquisar propriedades novas. Não use Grid, animações, sombras, posicionamento ou JavaScript.

---

## 🥟 Conteúdo obrigatório do cardápio

### Salgados

| Item | Ingredientes ou descrição | Preço |
| --- | --- | ---: |
| Coxinha de frango | Massa, frango desfiado e temperos da casa | R$ 7,00 |
| Coxinha com requeijão | Massa, frango desfiado e requeijão cremoso | R$ 8,00 |
| Pastel de carne | Massa, carne moída, cebola e azeitona | R$ 9,00 |
| Pastel de queijo | Massa, queijo muçarela e orégano | R$ 9,00 |
| Esfiha de carne | Massa assada, carne, tomate e cebola | R$ 7,00 |
| Enroladinho | Massa, salsicha e queijo | R$ 6,50 |

### Pizzas individuais

| Item | Ingredientes | Preço |
| --- | --- | ---: |
| Muçarela | Molho de tomate, muçarela, tomate e orégano | R$ 22,00 |
| Calabresa | Molho, muçarela, calabresa, cebola e orégano | R$ 24,00 |
| Frango com requeijão | Molho, muçarela, frango, requeijão e milho | R$ 26,00 |
| Portuguesa | Molho, muçarela, presunto, ovo, cebola e azeitona | R$ 27,00 |

### Bebidas

| Item | Descrição | Preço |
| --- | --- | ---: |
| Refrigerante lata | 350 ml | R$ 6,00 |
| Suco de polpa | 400 ml; consultar sabores | R$ 8,00 |
| Água mineral | 500 ml | R$ 4,00 |
| Café | 150 ml | R$ 4,00 |

### Porções e combos

| Item | Descrição | Preço |
| --- | --- | ---: |
| Batata frita | Pequena: R$ 12,00; grande: R$ 18,00 | a partir de R$ 12,00 |
| Mini salgados | 20 unidades variadas | R$ 28,00 |
| Combo Tentação | Um salgado tradicional e um refrigerante em lata | R$ 12,00 |

Inclua também este aviso:

> Os ingredientes podem variar conforme a disponibilidade. Em caso de alergia ou restrição alimentar, consulte a equipe antes de consumir.

## 📍 Dados fictícios da loja

- **Endereço:** Alto do Morro da Paz, 67 — Centro — General Sampaio-CE
- **Segunda a sábado:** 15h às 22h
- **Domingo:** 17h às 21h
- **Telefone:** (00) 90000-0000
- **E-mail:** contato@salgaderiatentacao.com

> [!WARNING]
> Não substitua esses dados por telefone, endereço, e-mail ou perfil pessoal de integrantes da equipe.

---

## 📁 Estrutura esperada

```text
projeto-03-salgaderia-tentacao/
├── index.html
├── FONTES.md
├── css/
│   └── estilos.css
└── imagens/
    ├── coxinha.jpg
    ├── pastel.jpg
    └── pizza.jpg
```

Os nomes das imagens podem ser diferentes, mas os caminhos precisam funcionar quando o projeto for aberto em outro computador.

## 🛠️ Etapas sugeridas

1. Observe os quatro prints e identifique `header`, `nav`, `main`, `section`, `article` e `footer`.
2. Crie as pastas e os arquivos.
3. Insira todo o conteúdo no HTML antes de iniciar o CSS.
4. Crie os links internos e teste cada destino.
5. Separe classes que poderão ser repetidas, como `.item-cardapio` e `.cartao-informacao`.
6. Aplique primeiro as cores e fontes gerais.
7. Depois trabalhe margens, preenchimentos, bordas e organização dos cartões.
8. Compare o navegador com os prints e corrija uma diferença por vez.

## 📦 Entrega

- Repositório sugerido: `projeto-03-salgaderia-tentacao`.
- Todos os arquivos devem estar dentro do repositório.
- Faça pelo menos três registros de versão: estrutura, conteúdo/estilo e correções finais.
- A entrega deve ser feita até o dia 28 de Outubro às 15:20.

---

<div align="center">

### 👀 Observe. 🧩 Divida em partes. 🛠️ Construa. 🔎 Compare e corrija.

</div>
