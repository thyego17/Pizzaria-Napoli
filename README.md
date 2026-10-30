# Pizzaria Napoli

Site de uma pizzaria fictícia, criado como projeto de portfólio por **Thyego**. O visitante conhece a casa, monta o pedido direto no cardápio e envia tudo pelo WhatsApp com a mensagem já pronta.

**Acesse:** [thyego17.github.io/Pizzaria-Napoli](https://thyego17.github.io/Pizzaria-Napoli/)

## Funcionalidades

- **Pedido pelo cardápio:** cada pizza tem botões − e + para escolher a quantidade.
- **Total em tempo real:** uma barra fixa no rodapé mostra o valor do pedido assim que o primeiro item é adicionado.
- **WhatsApp com mensagem pronta:** o botão "Enviar no WhatsApp" abre a conversa com a lista de pizzas, as quantidades e o total.
- **Terça da Pizza:** bloco de promoção (2 pizzas grandes + refrigerante 2L por R$ 89,90) com a etiqueta "É hoje!" que aparece sozinha às terças-feiras.
- **Status em tempo real:** uma etiqueta informa se a pizzaria está aberta ou fechada agora, respeitando o fechamento das segundas.
- **Contato rápido:** botões de telefone, e-mail e mapa.

## Cardápio

| Pizza | Preço |
| --- | --- |
| Margherita | R$ 45,00 |
| Calabresa | R$ 50,00 |
| Portuguesa | R$ 55,00 |
| Frango com Catupiry | R$ 60,00 |
| Quatro Queijos | R$ 58,00 |

## Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis CSS e animações)
- JavaScript puro, sem bibliotecas
- Fontes [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) e [Jost](https://fonts.google.com/specimen/Jost), via Google Fonts

## Design

- Visual elegante e acolhedor, com fundo marrom-tijolo escuro e acento em vermelho-tomate.
- Tipografia serifada em destaque e rótulos em caixa-alta espaçada.
- Layout responsivo, pensado primeiro para o celular.
- Foco visível, HTML semântico e respeito à preferência de movimento reduzido.

## Estrutura

```
Pizzaria-Napoli/
├── index.html
└── README.md
```

O site inteiro está em um único arquivo, com CSS e JavaScript incorporados.

## Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/thyego17/Pizzaria-Napoli.git
   ```
2. Abra o `index.html` no navegador.

Não é necessário instalar nada.

## Como personalizar

Tudo fica no `index.html`:

- **Pizzas e preços:** altere a lista `P` no início do script, no formato `["Nome", preço]`.
- **Número do WhatsApp:** troque `5511988888888` no script, usando código do país e DDD, sem espaços.
- **Promoção:** edite o bloco `Terça da Pizza` na seção de promoção. Para mudar o dia da etiqueta "É hoje!", altere o número em `if(d===2)` (0 é domingo, 1 é segunda, e assim por diante).
- **Horário de funcionamento:** ajuste a linha `const open=...` no script (hoje fecha às segundas e funciona das 18h às 23h) e o texto na seção de contato.
- **Cores:** edite as variáveis em `:root`, no início do `<style>`.

## Observações

Este é um projeto de demonstração. Nome, endereço, telefone, e-mail e preços são fictícios, e nenhum pedido é processado de verdade: o site apenas abre o WhatsApp com a mensagem montada.

## Autor

**Thyego**

- Portfólio: [thyego17.github.io/Portif-lio](https://thyego17.github.io/Portif-lio/)
- GitHub: [@thyego17](https://github.com/thyego17)
