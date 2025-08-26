# Minha Loja Online (GitHub Pages)

Site de vendas simples (front-end puro) para publicar no **GitHub Pages**. Inclui:
- Home, Produtos e Checkout
- Lista de produtos renderizada no navegador
- Pagamento **simples via Pix** (exibe a chave e botão de copiar)

> **Importante:** Por ser site estático, não há back-end aqui. Para pagamentos automáticos (Pix com QR/validação, Stripe, Mercado Pago), será preciso usar um servidor ou serviços de terceiros.

## Como usar

1. Edite a chave Pix no arquivo `checkout.html` (elemento `<code id="pixKey">`).
2. Edite os produtos no arquivo `js/script.js` (constante `PRODUTOS`).
3. Publique no GitHub Pages:

### Publicar no GitHub Pages
- Crie um repositório, por exemplo: `loja-online`.
- Envie estes arquivos para a branch `main`.
- No GitHub: **Settings → Pages → Source: Deploy from a branch** e selecione `main / (root)`.
- O link ficará: `https://SEU_USUARIO.github.io/loja-online/`

## Personalização rápida
- Cores/estilo: `css/style.css`
- Produtos: `js/script.js`
- Texto da Home: `index.html`
- Título do produto no checkout é lido do parâmetro `?produto=...` na URL.

## Suporte/Contato
Coloque aqui seu WhatsApp/Telegram para receber comprovantes e liberar acessos.
