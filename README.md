# bootstrap-emkt

Bootstrap HTML para criação de e-mail marketing procurando a utilização das melhores práticas de desenvolvimento.

## Fontes

O layout necessita de uma fonte específica? [Clique aqui](https://www.campaignmonitor.com/blog/email-marketing/2016/07/10-things-need-know-web-fonts-email-right-now/) e [aqui](https://www.campaignmonitor.com/blog/email-marketing/2012/12/using-web-fonts-in-email/) e veja tudo o que precisa saber sobre fontes em e-mails.

### Realização de testes
1. Começar pelo [PutsMail](https://putsmail.com/) que envia um e-mail para vários endereços de uma só vez
2. O [Mail Tester](http://www.mail-tester.com/) para a correção de dados
3. Use o [Post Image](http://postimage.org) para realizar o upload das imagens

### Observações
1. É necessário a inclusão de e-mail também no formato de texto - text/plain - caso o seu servidor não possua: `$ Content-Type: text/plain; charset=us-ascii`. Leia mais sobre em [Why Multi-Part Email is Important](https://litmus.com/blog/reach-more-people-and-improve-your-spam-score-why-multi-part-email-is-important)
2. Para saber quais propriedades funcionam em devido cliente de e-mail, acesse o [Campaign Monitor](https://www.campaignmonitor.com/css/)
3. Escreva o css entre as tags `<style type="text/css"></style>` e cole o HTML no [Premailer](http://premailer.dialect.ca) ou no [CSS Inliner Tool](http://templates.mailchimp.com/resources/inline-css/). Isso fará com o que os atributos css sejam declarados inline.
4. Para backgrounds em Outlook, use o [Backgrounds](http://backgrounds.cm) para gerar o cógido.
