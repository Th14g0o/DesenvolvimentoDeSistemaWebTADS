# Introdução ao Django

## Estilo MVT(Model-View-Template)

**Estrutura de aplicação. Requisições(Request) são feitas a camada View, esta processa e utiliza o Model para obter ou gerenciar dadoes e por fim devolve um Template renderizado ao navegador do usuário como resposta(Response).**

**Model**: Mapea e gerencia dados da aplicação. Uma representação da estrutura do banco(Via ORM). Define regras de negocio.

**Template**: Apresentação visual, camada responsavel por renderizar o HTML e exibir dados de forma interativa e/ou estatica. (HTML + tags Django)

**View**: Controla o fluxo da aplixação. Lógica de processameno das requisições. Conecta modelo de dados e template.

## Django

- Frame work de alto nível.
- **Batteries included**: ja entrega muita coisa util para facilitar o desenvolvimento. E tem uma estrutura bem definida. ORM, Forms, admin, cache,...
- **Segurança embutida**: CSRF, XSS, Sql Injection, Clickjacking.
- **Escalabilidade e robustez**
- **Comunidade ativa**
- **Ferramentas adicionais**: Admin automatico, migrations, middlewares, REST com Django RestFramework.