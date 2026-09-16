# Site Moldou 3D

Site estático (HTML/CSS/JS puro) pronto pra hospedar no GitHub Pages.

## Estrutura
```
index.html
css/style.css
js/script.js
images/  (logo + fotos dos produtos)
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `moldou3d`).
2. Suba todos os arquivos desta pasta pra raiz do repositório (mantendo a estrutura de pastas).
3. No repositório, vá em **Settings → Pages**.
4. Em "Branch", selecione `main` e a pasta `/root`, depois clique em **Save**.
5. Em alguns minutos seu site estará no ar em `https://SEU-USUARIO.github.io/moldou3d/`.

## O que revisar antes de publicar

- **Preços conferidos**: no seu texto, o preço do Harry Potter e do Mascote do Galo vieram meio trocados entre os títulos — usei R$ 85,90 pro Harry Potter e R$ 89,90 pro Mascote do Galo. Confirme se está certo.
- **Escultura Pet Personalizada**: ficou sem preço definido ("Sob consulta") porque não veio na sua mensagem — é só editar o texto `Sob consulta` no `index.html` pelo valor real, dentro do card `product-card` da escultura pet.
- **Descrição "Sobre a Moldou 3D"**: escrevi um texto baseado no que você me contou. Fique à vontade pra ajustar o tom ou os detalhes.
- **Número do WhatsApp**: usei `5561998520978`. Se quiser trocar, é só substituir esse número em todos os links `wa.me/` do `index.html` (dá pra usar Ctrl+H / buscar e substituir).

## Editar textos e preços
Basta abrir o `index.html` num editor de texto (ex: VS Code, Notepad++) e alterar o conteúdo dentro das tags — não precisa saber programar, é só trocar o texto.
