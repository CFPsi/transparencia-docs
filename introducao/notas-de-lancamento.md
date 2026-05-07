# Notas de lançamento

## Versão 1.5.0 (23/11/2020)

### &#x20;Melhoria:

* Alterações gerais para atender a IN 84/2020 - TCU;
* Inclusão do Portal da Transparência do CRP 24.

## Versão 1.4.0 (14/02/2020)

### Funcionalidade:

* (CRP06) Importação de Ajudas de Custo
* Cadastro e-Psi: página com estatísticas de aprovação e reprovação de cadastros no e-Psi.
* No painel do administrador, atalho para corrigir alguns links quebrados.
* (CRP11) Folhas de Pagamentos: trazer resultados no primeiro acesso.

### Melhoria:

* Folhas de pagamentos: possibilidade de ordenar os campos da forma que for desejado.
* Aprimoramento da paginação de algumas páginas (Relação de Pagamentos)
* Versão do PHP (parte do servidor) atualizada para 7.2, melhorando estabilidade e performance.
* Migração do PHPExcel para PHPSpreadsheet, biblioteca mais moderna de manuseio de planilhas.
* Migração do Html2Pdf para WkHtmltopdf, biblioteca mais moderna de geração de PDF.
* Relação de pagamentos: geração de PDF de forma assíncrona.
* Refatorações internas para melhorar desempenho e organização.

### Correção:

* Despesas/Receitas (importação): ajustes para novo layout de CSV do Siscont
* Folhas de Pagamentos (importação): impedir envio de arquivos que não sejam XLS ou XLSX.
* Correção de erros acusados na ferramenta de diagnósticos.
* Correção da geração de XML de Testes psicológicos

## Versão 1.2.0 (10/04/2018)

### Funcionalidade:

* Contratos, Licitações e Convênios: download de resultados em CSV e PDF.
* Whitelist para reCaptcha: lista de IPs que não precisam preencher "Não sou um robô".
* Registro de atividades (logs) para importações de Folhas de Pagamentos e Prestação de Contas.
* Opção de pesquisar por pagamentos do tipo "Restos a pagar".
* Contratos e Licitações: link para versão antiga selecionando o ano "Anteriores...".

### Melhoria:

* Melhor aplicação do tema de alto contraste.
* Ordenação de perguntas frequentes.
* Adição de paginação nas páginas de pesquisa.
* Melhorias de usabilidade na busca de Folhas de Pagamento.
* Melhor identificação e leitura de datas ao importar Folhas de Pagamentos.
* Refatorações internas para melhorar desempenho e organização.
* Remoção, no painel de acesso restrito, menus para alterar Contratos e Licitações. Agora esses dados são buscados do sistema de Gestão de Contratos.

### Correção:

* Correção de erro dos filtros compostos em regionais.
* Correção de menu sendo exibido por baixo dos outros conteúdos.
* Correção de problema ao baixar Relação de Pagamentos em PDF.
* Parar de exibir erros se usuário ainda não submeteu formulário.
* Corrigido erro ao pesquisar Folhas de Pagamento por campos do tipo texto.

## Versão 1.1.0 (07/06/2017)

### Melhoria:

* Exibição do tamanho e extensão dos arquivos hospedados no Portal da Transparência;
* Exibição de ícone de nova aba quando link abre em nova aba;
* Interface melhor para a área de importação de Prestação de Contas e Folhas de Pagamento;
* Adição de SSL para implementar HTTPS no site, aprimorando a segurança.

### Funcionalidade:

* Convênios: exibição dos arquivos anexos ao convênio;
* Adicionado CRP06;
* Inclusão de categorização de Comissões por caráter;
* Adição de filtros compostos para as áreas com categorias (Institucional, Legislação, Planejamento, ...).
* Atualização dos dados de Cadastros de Sites e Testes Psicológicos de forma automática;
* Adição do tipo de prestação de conta "Restos a pagar".

### Correção

* Correção de dados dos detalhes de contrato;
* Contratos: ao pesquisar por modalidade, considerar também a modalidade da licitação.

## Versão 1.0.1 (12/04/2017)

### Melhoria:

* Inclusão dos ícones e extensão dos arquivos nos links de download (#6 \[closed])
* Abrir links de documentos em uma nova aba (#4 \[closed])
* Alteração da url da área restrita para /painel (#17 \[closed])

### Correção:

* Exibição de "Contratos" quando não inserida a modalidade (#14 \[closed])
* Alterar o alvo (target) do link na página "Cadastros de sites" e "Testes psicológicos" para \_blank (#15 \[closed])
* Formulário "Perdeu a senha?" (#18 \[closed])
* Problema na coluna "ano" da página "Cadastros de sites" no site do CRP 21 (#16 \[closed])
* Problema ao enviar arquivo CSV para a biblioteca do WordPress (#10 \[closed])

## Versão 1.0.0 (15/02/2017)

### Funcionalidade:

* Recursos de Acessibilidade
* Design Responsivo e Mobile First
* Barra lateral com _widgets_ dinânima
* Documentação para Desenvolvedores WordPress
* Inclusão das áreas:
  * Concurso
  * Gestão
  * Comissão
  * Ata
  * Legislação
  * Planejamento
  * Finança
  * Licitação
  * Contrato
  * Chamada Pública (#1)
  * Folha de Pagamento
  * Passagem e Diária
  * Pergunta Frequente
  * Eleição
* Navegação por migalhas de pão através do plugin Breadcrumb NavXT
* Inclusão do shortcode incorporar

### Melhoria:

* Inclusão do ícone do site através da _Site Icon API_ do WordPress
* Adição de suporte a logotipo personalizado
* Personalização do tema através da _The Customizer API_
* Inclusão de código de acompanhamento do _Google Analytics_ personalizado
* Inclusão da mensagem "Este link abrirá em uma nova janela" em todos os links externos
* Inclusão de paginação nas páginas de arquivo
* Ocultado a área de posts no menu do painel
* Customização da cor do link na área de conteúdo do site (#3)
* Ordenar corretamente "Eleições" no menu do painel administrativo (#5)

### Correção:

* Correção nos tamanhos do logotipo mobile/desktop
* Atualização de links quebrados na página de Acessibilidade
* Correções de Dados Estruturados para o Google Webmasters
* Substituição da logo do CFP
* Colocando o sub-menu acima do campo de pesquisa na página de busca
