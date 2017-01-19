# tt-shortcodes-light
Versão sem instalador do plugin de shortcodes para WordPress.


## Resumo

Esta é a *versão de produção* do plugin **TT Shortcodes**, exatamente como descrito no artigo do [Tutoriart](https://www.tutoriart.com.br/?p=8941). Ela não tem instalação automática e foi feita com o tema [Twenty Seventeen](https://br.wordpress.org/themes/twentyseventeen) em foco, embora possa ser aplicado a qualquer outro seguindo as instruções (e sabendo o que está fazendo).


### Pré-requisitos

O que você precisa para usar esta versão:

* Uma instalação do WordPress (óbvio, não?)
* O tema Twenty Seventeen se quiser seguir as instruções à risca, ou qualquer outro se souber como criar temas filho e editar / criar um arquivo de funções (functions.php)
* Um tema filho ajustado e em uso


### Instalação

A instalação é manual:

1. Copie a pasta "admin" para a pasta do seu tema filho (no caso, a "twentyseventeen-child")
2. Abra o arquivo functions.php do tema filho e insira:
```
require_once('admin/tt-functions.php');
```
Se tudo estiver certo, é só abrir o editor de posts, e a caixa de inserção de shortcodes estará lá.


### Possíveis erros

Caixa não apareceu: confira se houve erros na inclusão das funções, verifique o console do navegador por erros.

Ícones não aparecendo: os ícones dependem do BootstrapCDN que fornece os arquivos necessários do FontAwesome.


## Importante

Estes scripts e estilos foram testados em sites de teste e produção, sem problemas, mas note que são distribuídos "no estado", sem qualquer garantia de funcionamento e/ou qualidade.

Além disso, estão em contínuo desenvolvimento e podem ser alterados a qualquer momento, com adição ou remoção de partes ou dele todo.

Sempre faça backup do seu banco de dados antes de utilizar em sites de produção. Não nos responsabilizamos por possíveis erros catastróficos, embora nenhum seja provável ou tenha sido observado.


## Créditos

* [FontAwesome](http://fontawesome.io/) - ícones
* [BootstrapCDN](https://www.bootstrapcdn.com/fontawesome/) - CDN


## Autores

* **Daniel Lemes** - *Trabalho inicial* - [DanielLemes](https://github.com/DanielLemes)


## Contribuições

Leia o nosso readme CONTRIBUA se quiser colaborar com o desenvolvimento de qualquer forma.


## Licença

Este projeto está sob licença [GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), exceto quando especificado o contrário.
