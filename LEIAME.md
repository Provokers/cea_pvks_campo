# C&A Campo · Provokers

## Publicar no GitHub Pages
1. Crie um repositório e suba todos os arquivos desta pasta na raiz.
2. Settings > Pages > Deploy from branch > main / root.

## Atualizar informações
Edite apenas `data.json` e altere o campo `versao`. Quem abrir com internet recebe na hora; offline, vale a última versão salva.
Aviso no topo da agenda: `"avisos": ["Visita das 15h atrasada 30 min"]`.

## Uber com destino preenchido
O Uber só garante o destino preenchido quando recebe coordenadas. Em cada visita, adicione `"lat"` e `"lng"`
(no Google Maps: toque e segure no endereço, copie os números). Ex.: `"lat": -23.5401, "lng": -46.5768`.
Sem coordenadas, o app envia só o endereço em texto.

## Senha
Validação local por hash (PVKS2026!). Barreira de acesso, não criptografia: o data.json fica acessível pela URL direta.
