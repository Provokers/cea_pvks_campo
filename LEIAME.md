# C&A Campo · Provokers

## Publicar no GitHub Pages
1. Crie um repositório (pode ser privado com Pages habilitado no plano pago, ou público).
2. Suba todos os arquivos desta pasta na raiz.
3. Settings > Pages > Deploy from branch > main / root.

## Atualizar informações
Edite apenas `data.json` (agenda, manual, contatos, avisos) e altere o campo `versao`.
Quem abrir o app com internet recebe a atualização na hora. Offline, o app mostra a última versão salva.
Para exibir um aviso no topo da agenda: `"avisos": ["Visita das 15h atrasada 30 min"]`.

## Senha
Validação local por hash (PVKS2026!). Funciona como barreira de acesso, mas não é criptografia do conteúdo: o data.json fica público na URL.
