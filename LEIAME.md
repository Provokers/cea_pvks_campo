# C&A Campo · Provokers

## Publicar no GitHub Pages
1. Crie um repositório e suba todos os arquivos desta pasta na raiz.
2. Settings > Pages > Deploy from branch > main / root.

## Atualizar informações
Edite apenas `data.json` e altere o campo `versao`. Quem abrir com internet recebe na hora; offline, vale a última versão salva.
Aviso no topo da agenda: `"avisos": ["Visita das 15h atrasada 30 min"]`.

## Mapa e Uber
Mapa: no Android abre o app de mapas padrão. No iPhone, na primeira vez a pessoa escolhe entre Apple Maps, Google Maps e Waze; a escolha fica salva e pode ser trocada na aba Contatos.
Uber: o botão copia o endereço e abre o app do Uber. É só colar no campo de destino.

## Senha
Validação local por hash (PVKS2026!). Barreira de acesso, não criptografia: o data.json fica acessível pela URL direta.
