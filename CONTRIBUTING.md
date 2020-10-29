# Guia de Contribuição

## Antes de Contribuir

Brm vindo ao [Feed To Telegram](https://github.com/lariodiniz/feedToTelegram)! Antes de enviar seus pull requests, leia todo nosso **guia de contribuição**. Se você tiver qualquer dúvida sobre esse guia, fique a vontade para faze-la no nosso [issue](https://github.com/lariodiniz/feedToTelegram/issues/new).

## Contribuição


### Contribuidor

Agradecemos que você considere contribuir para o [Feed To Telegram](https://github.com/lariodiniz/feedToTelegram)! Nosso objetivo é ajudar a comunidade da podosfera a divilgar seus podcasts para o máximo de pessoas possiveis. Sendo um de nossos colaboradores, você concorda e confirma que:

- Seu trabalho será distribuído sob a [MIT License](LICENSE.md) assim que seu pull request for mesclado.
- Você enviou um código que siga o nosso **Estilo de Codificação**
- Você escreveu testes para o seu código.

**Melhorar Comentários** e **Melhorar os testes** também são bem-vindos.

Agradecemos qualquer contribuição, desde correções em erros de gramática até algoritmos complexos.

### Fluxo de Trabalho
 Nota: Sugerimos a utilização de uma virtualização para a contribuição desse projeto, utilizamos o [Anaconta](https://www.anaconda.com/download/).

 01 - Instale o [Python 3.8+](https://www.python.org/downloads/).

 02 - Instale os [Requerimentos](requirements.txt)

 03 - Faça um fork desse projeto para a sua conta GitHub clicando no botão Fork.

 04 - Clone essa cópia do reposítorio para a sua maquina.

 ```
 git clone https://github.com/[seuNomeDeUsuarioDoGitHub]/feedToTelegram.git
 ```

 05 - Acesse a pasta clonada pelo terminal.

 06 - Defina o projeto principal como um novo remote no seu projeto para você ter acesso as mudanças que forem adicionadas nele.

 ```
 git remote add upstream https://github.com/lariodiniz/feedToTelegram.git
 ```

 07 - Inicie o git flow no seu diretório do projeto. (Mais informaçoes sobre o [git-flow](https://medium.com/@lariodiniz/tutorial-git-com-git-flow-476ad906c8ae))

 08 - Crie um braço para desenvolvimento a partir do braço develop.

 09 - Faça suas alterações.

 10 - Execute todos os testes.

 11 - Faça um Push para o seu repositório de origem.

 12 - Faça um Pull Request para o projeto original.


#### Estilo de Codificação

- Escreva em Python 3.8+
- Siga as diretrizes da [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Escreva o código em Inglês.
- Faça nomes descritivos para as suas variáveis, funções e classes.
  - Evite nomes de variáveis com uma única letra.

- Escreva DocStrings e Comentários para seu código.
- Se você precisar de um módulo de terceiros que não esteja no arquivo __requirements.txt__, Adicione-o a esse arquivo como parte do seu envio.


Escrito por [@lariodiniz](https://github.com/lariodiniz), Outubro 2020.
