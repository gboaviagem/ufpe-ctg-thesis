# Template de Tese de Doutorado em LaTeX para o CTG/UFPE

Este repositório contém um template em LaTeX para teses de doutorado (e possivelmente mestrado) dos alunos do **Centro de Tecnologia e Geociências (CTG) da Universidade Federal de Pernambuco (UFPE)**. O template é exatamente aquele que precisei customizar para ter a **[minha Tese](https://github.com/gboaviagem/phd-thesis)** aprovada em maio de 2023 pela Biblioteca do CTG. Ele segue aquele [disponibilizado pela UFPE](https://www.ufpe.br/documents/39058/594591/Modelo+de+Tese+e+Disserta%C3%A7%C3%A3o+em+PDF/b833b955-19fd-4e7e-8c03-855de6b67bbe), mas que não tem versão em LaTeX.

Veja **[aqui o template em PDF](./thesis/out/main.pdf)**.

Algumas das exigências da Biblioteca do CTG (que por vezes nem se encontram ipsis litteris na ABNT) que estão neste template (e não são contemplados pela versão default do abnTeX2):

- Todo o trabalho deve ser digitado em fonte padrão tamanho 12, inclusive as informações da capa, títulos de capítulos e seções.
- A contagem das folhas inicia na folha de rosto (2ª folha).
- A apresentação gráfica do Resumo/Abstract deve seguir o mesmo padrão do corpo do trabalho, ou seja,  texto digitado em espaço 1,5 entre linhas, justificado com recuo inicial na primeira linha (parágrafo).
- As palavras-chave/keyword devem vir separadas por ponto-e-vírgula, em minúsculas exceto se for nome próprio. O termo "palavra-chave"/"keyword" não pode estar em negrito e deve ter recuo inicial (parágrafo).
- As páginas não podem ter cabeçalho indicando o capítulo/seção atual.

## Como utilizar o template

Novos doutorandos são convidados a utilizarem este repositório como template de suas teses desde o início, para evitarem o desgaste de revisões e edições do layout em LaTeX, devido à falta de adequação com as normas da Biblioteca do CTG.

Para utilizar o template, basta clonar este repositório e preencher com os arquivos de sua tese.

Observação:

- O arquivo `ufpe-ctg-thesis/thesis/preamble_class.tex` edita partes automáticas da classe abnTeX2, como a folha de rosto. Sempre que precisar customizá-las, edite lá!


## Customização da classe abnTeX2

Este repositório utiliza uma versão bastante customizada da classe abnTeX2, a fim de cumprir todas as (muitas!) especificidades exigidas pela Biblioteca do CTG. Os responsáveis pela customização da classe são:

- Guilherme Boaviagem (guilherme.boaviagem@gmail.com)
- José Neto (https://github.com/joneto, @jometo)
- Caio Vital (caio.vital@gmail.com)

## Contribuições

É possível que algum detalhe das normas fuja a este template, por isso incentivo **os usuários a abrirem "issues" ou "pull requests" aqui no repositório**, para melhoria e benefício dos futuros usuários.

## Licença

Este template é distribuído sob a licença GNU GPL v3.0. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
