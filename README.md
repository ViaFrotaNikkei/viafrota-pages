# ViaFrota — publicação

Aplicativo ViaFrota, **Atualização nº 55**.

Acesse: https://viafrotanikkei.github.io/viafrota-pages/?v=55

Site principal: https://nikkeilogistica.com.br/viafrota/?v=55

O Master pode editar, aprovar e recusar ordens pendentes no Operacional, assim como o responsável escolhido. Após editar, a tela de confirmação de aprovação abre com os dados salvos. O histórico e o responsável são preservados.

Este repositório contém somente arquivos públicos do site. Desenvolvimento, testes e migrações ficam no projeto privado ViaFrotaNikkei/viafrota; dados e documentos permanecem protegidos por autenticação e RLS do Supabase.

Artefato do commit 5d96f0c0bb0c5ac59b148394ac5a6bf7cb948e9e: 17 suítes JavaScript, 638 verificações, mais 26 verificações de RPC/RLS da v55 e 39 de regressão da v54 com rollback. Fluxo conferido no navegador com dados simulados. Nenhuma ordem real foi alterada nos testes. O index.html usa o blob 914a77bf3e8ef274dfa252ee5ba57624c630384b, idêntico ao arquivo testado e publicado no domínio principal.

GitHub Pages publica main, pasta raiz. Recuperação de senha e confirmação de e-mail continuam retornando ao domínio principal conforme a configuração existente.
