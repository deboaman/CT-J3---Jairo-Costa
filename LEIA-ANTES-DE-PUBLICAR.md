# CT-3J Jiu-Jitsu — pacote do site

Abra `index.html` para visualizar a página inicial. As versões de seminários ficam em `seminarios.html` (português) e `seminars.html` (inglês).

## Hospedar pelo Cloudflare Pages

1. Baixe o arquivo `CT-3J-site-pronto-para-hospedagem.zip`. Você pode enviar o ZIP diretamente ou extraí-lo e enviar a pasta.
2. Crie uma conta ou entre no Cloudflare.
3. Abra **Workers & Pages**, escolha **Create application**, depois **Get started** e **Drag and drop your files**.
4. Dê um nome ao projeto e envie o ZIP ou a pasta `ct3j-site-publicacao` extraída.
5. Selecione **Deploy site**. O Cloudflare mostrará um endereço terminando em `pages.dev`.

Esse fluxo faz uma publicação manual. Se você quiser atualizações automáticas conectadas ao GitHub/GitLab, escolha a integração Git desde o início: projetos criados por Direct Upload não podem ser convertidos depois para integração Git.

Para usar um domínio próprio, primeiro publique e teste o endereço `pages.dev`. Depois, em **Workers & Pages > projeto > Custom domains**, conecte o domínio. O domínio precisa estar registrado; o serviço de Pages não compra o domínio para você.

## Conferências antes de divulgar o endereço

- Confirmar com Jairo que o telefone e o WhatsApp podem aparecer publicamente.
- Confirmar autorização de uso das fotos, especialmente das imagens de crianças e adolescentes.
- Confirmar que o uso público dos emblemas enviados atende às orientações das respectivas equipes.
- Conferir no celular os links de WhatsApp, Instagram, navegação e idioma.
- Quando houver domínio próprio, configurar HTTPS e atualizar as informações de compartilhamento e indexação com o domínio final.
- Completar endereço, horários, categorias de aula e dados institucionais somente depois de confirmação da equipe.

O pacote apresenta o CT-3J e permite contato pelo WhatsApp. Ele não configura Perfil da Empresa no Google ou e-mail institucional.

## Documentação oficial

- [Cloudflare Pages: envio direto por ZIP ou pasta](https://developers.cloudflare.com/pages/get-started/direct-upload/)
- [Cloudflare Pages: configurar domínio próprio](https://developers.cloudflare.com/pages/configuration/custom-domains/)
