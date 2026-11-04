# Nailux Esmalteria — site institucional

Site estático responsivo em HTML, CSS e JavaScript, adaptado para a Nailux Esmalteria, no Água Verde, Curitiba. Inclui imagens fornecidas, links para Instagram, WhatsApp e localização, além de formulário que prepara o pedido de agendamento no WhatsApp.

## Preview local (Windows / PowerShell)

Na pasta raiz do projeto, execute:

```powershell
py -m http.server 5432 --bind 0.0.0.0
```

Acesse `http://localhost:5432`. O servidor deve ser iniciado na pasta que contém o `index.html`.

## Estrutura

- `index.html` — conteúdo, SEO local e dados estruturados.
- `css/style.css` — estilo e responsividade.
- `js/main.js` — menu, animações, data mínima e formulário WhatsApp.
- `assets/nailux/` — imagens e logo recebidas.
- `vercel.json` — headers estáticos para Vercel.

Não requer `npm install` nem etapa de build.

## Tipografia do hero (prévia)

O hero usa **Milesdane Trial** para avaliação visual. A versão do DaFont é licenciada apenas para uso pessoal; não faça commit, publicação ou apresentação comercial com essa fonte antes de adquirir a licença comercial. Antes de publicar para a Nailux, substitua pelo arquivo coberto pela licença comercial ou use uma alternativa comercialmente liberada. Fonte de referência: https://www.dafont.com/milesdane.font

## GitHub e Vercel

O site pode ser mantido em um repositório GitHub e implantado na Vercel como site estático. Na Vercel, use o preset **Other** e deixe a pasta raiz do projeto como diretório de publicação. Não publique até a aprovação final da responsável pelo negócio.

Antes de um deploy público, confirme com a Nailux os serviços, os textos comerciais e os números do perfil do Instagram. Defina também o domínio definitivo e preencha as URLs canônicas em `robots.txt` e `sitemap.xml` (e adicione metadados de URL/imagem social ao HTML quando o domínio estiver definido). As métricas do Instagram exibidas são as informadas para esta versão e podem mudar.
