# C&A Campo · Provokers

## Publicar no GitHub Pages
Suba todos os arquivos desta pasta na raiz do repositório (substituindo os atuais).

## Praças
Cada praça é um item em `pracas` no `data.json`, com `uf`, `nome`, `cidade`, `inicio`, `dias` e `contatos` (Provokers).
O app abre sempre na praça com `inicio` mais recente. As demais aparecem no seletor em cinza, só para consulta.
Para adicionar um estado novo, copie o bloco de uma praça, preencha e troque o campo `versao`.

## Atualizar informações
Edite `data.json` e altere `versao`. Quem abrir com internet recebe na hora; offline, vale a última versão salva.
Equipe por visita: `provokers` e `cea`. Lista vazia aparece como "A confirmar".
Loja de rua: `"formato": "rua"` (o card mostra reencontro na loja em vez de no shopping).
Contatos C&A ficam em `contatos` na raiz; contatos Provokers ficam dentro de cada praça.

## Senha
Validação local por hash (PVKS2026!). O data.json fica acessível pela URL direta.
