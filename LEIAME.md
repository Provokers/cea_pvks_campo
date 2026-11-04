# C&A Campo · Provokers

O conteúdo do app (praças, visitas, equipes e contatos) vem de uma planilha no Google Sheets.
O GitHub guarda só o app. O manual de campo fica fixo no app.

## Configuração
Planilha: https://docs.google.com/spreadsheets/d/1R7VLmklPGNIbUHXLVoBXer4sS1CpRMi90Ze1v4-_tdc/edit
O `config.json` já aponta para as abas Praças, Visitas e Contatos dessa planilha.
Para o app conseguir ler, a planilha precisa estar em Compartilhar > Acesso geral > Qualquer pessoa com o link > Leitor.
Edição continua restrita a quem foi convidado.
Não renomeie as abas: o app procura pelos nomes Praças, Visitas e Contatos.

## Como o app se comporta
- Lê a planilha toda vez que é aberto com internet e guarda uma cópia para funcionar offline.
- Se a planilha estiver fora do ar ou com erro, mantém a última versão boa.
- Abre na praça em campo hoje ou na próxima. Praças encerradas ficam em cinza.
- Praças com Publicar = Não não aparecem.
- Enquanto o `config.json` estiver vazio, o app usa os dados embutidos nesta versão.

## Privacidade
A planilha publicada pode ser lida por quem tiver o link. Não coloque nela dados do questionário.
Senha do app: validação local (PVKS2026!).
