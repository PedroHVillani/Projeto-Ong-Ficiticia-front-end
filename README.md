# Projeto-Ong-Ficiticia-front-end
# Luta pelo Futuro

Projeto acadêmico de front-end que representa uma ONG fictícia voltada à inclusão social de crianças e adolescentes por meio do esporte e das artes marciais.

A aplicação foi desenvolvida como uma Single Page Application (SPA), utilizando HTML, CSS e JavaScript.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- DOM
- localStorage
- Day.js via CDN
- Git e GitFlow
- Live Server

## Estrutura do projeto

O projeto está organizado em pastas específicas para HTML, CSS, imagens e JavaScript.

A interface utiliza HTML semântico, CSS responsivo, Grid e Flexbox.

A navegação da SPA é controlada pelo JavaScript através de rotas baseadas em hash.

## Funcionalidades

- Navegação SPA sem recarregamento completo da página
- Página inicial institucional
- Área de projetos e voluntariado
- Formulário de cadastro
- Validação de campos
- Alertas e toast
- Menu responsivo
- Templates JavaScript
- Persistência com localStorage
- Registro do último acesso
- Integração com Day.js

## Execução do projeto

Não existem dependências que precisem ser instaladas por NPM.

O projeto pode ser executado através do Live Server no VS Code.

Também pode ser iniciado com Python:

```bash
python -m http.server 5500

Build
O projeto utiliza HTML, CSS e JavaScript puros e não necessita de processo de build ou compilação.
Os arquivos podem ser executados diretamente em um servidor HTTP local.
Testes
Os testes foram realizados manualmente utilizando as ferramentas de desenvolvimento do navegador.
Foram avaliados:
- navegação entre rotas;
- validação de formulários;
- campos inválidos;
- localStorage;
- carregamento das imagens;
- comportamento responsivo;
- falha no carregamento do Day.js;
- eventos e manipulação do DOM.
Controle de versão
O projeto utiliza Git com organização inspirada no GitFlow.
Branches principais:
- main: versão estável;
- develop: desenvolvimento;
- feature/: novas funcionalidades;
- hotfix/: correções urgentes;
- release/: preparação de versões.
As mensagens seguem o padrão Conventional Commits.
Versionamento
Foi adotado o versionamento semântico MAJOR.MINOR.PATCH.
Exemplos:
- v1.0.0: primeira versão estável;
- v1.0.1: correção de falhas sem alteração incompatível.
Observação
Este projeto foi desenvolvido exclusivamente para fins acadêmicos. A ONG Luta pelo Futuro é fictícia.
