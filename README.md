# Portal da Soberana

Página responsiva da fila de espera da imersão presencial, com a foto fornecida, identidade em vinho e dourado e acesso ao formulário oficial de inscrição.

## Executar

Requer Python 3. Na pasta do repositório:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

Também é possível executar `npm run dev`. Não há dependências a instalar nem etapa de build. `npm run check` verifica a sintaxe do JavaScript.

## Inscrições

As chamadas principais levam à seção de inscrição, com acesso ao Google Forms oficial fornecido pela responsável. Os dados são preenchidos e enviados no Google Forms, sem armazenamento nesta página. O link de contato abre o WhatsApp +55 62 98226-7172, conforme a referência fornecida.

A data e o local da próxima edição não foram informados. A página não inventa esses detalhes. Fontes do Google Fonts são opcionais: há fontes locais de fallback. A fotografia está em `assets/samara.jpg`.

## Publicar pelo navegador (GitHub Pages)

1. Revise o commit da página no GitHub e incorpore a branch `site/portal-da-soberana` em `main` por uma pull request.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch **main**, pasta **/ (root)** e clique em **Save**.
5. Aguarde a conclusão da publicação. O próprio painel Pages exibirá o endereço ativo.

O endereço padrão esperado é `https://marianasouzalitoral-maker.github.io/paginamodelosamara/`. Ele só ficará disponível depois de ativar e concluir a publicação. Pode ser acessado pelo celular e pelo computador. Em repositório privado, a disponibilidade do Pages depende do plano do GitHub.

Para uma prévia pública antes do merge, é possível selecionar a branch `site/portal-da-soberana` no Pages, em vez de `main`. Isso publica o conteúdo dessa branch. Depois do merge, altere a origem para `main`.

Nenhuma instalação local é necessária. O site não tem etapa de build; `index.html`, `styles.css`, `script.js` e a pasta `assets` bastam para hospedagem estática. Os links de Google Forms, Instagram e WhatsApp devem ser preservados sem autorização explícita para alterá-los.
