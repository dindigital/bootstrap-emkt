# bootstrap-emkt

Bootstrap HTML para criação de e-mail marketing procurando a utilização das melhores práticas de desenvolvimento.

### Realização de testes
1. Começar pelo [PutsMail](https://putsmail.com/) que envia um e-mail para vários endereços de uma só vez
2. O [Mail Tester](http://www.mail-tester.com/) para a correção de dados

### Observações
1. É necessário a inclusão de e-mail também no formato de texto - text/plain - caso o seu servidor não possua: `$ Content-Type: text/plain; charset=us-ascii`. Leia mais sobre em [Why Multi-Part Email is Important](https://litmus.com/blog/reach-more-people-and-improve-your-spam-score-why-multi-part-email-is-important)
2. Escreva o css entre as tags `<style type="text/css"></style>` e cole o HTML no [Premailer](http://premailer.dialect.ca). Ele fará com o que os atributos css sejam declarados inline.