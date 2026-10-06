# Mapa das unidades PUC Minas (Mapbox)

## Estrutura

```
mapa-puc-minas/
├── index.html
├── css/style.css
└── js/
    ├── config.js   ← token do Mapbox
    └── app.js      ← lógica do mapa
```

## Onde colocar o token

Abra `js/config.js` e troque `SEU_TOKEN_AQUI` pelo seu token público (começa com `pk.`).
Você encontra/cria o token em https://account.mapbox.com/access-tokens/

## Como rodar

O projeto usa só HTML, CSS e JavaScript.

- **Jeito mais simples:** abra o `index.html` no navegador (duplo clique). O mapa e os marcadores aparecem normalmente.
- **Se o marcador "Estou aqui!!!" não aparecer:** alguns navegadores bloqueiam a localização em arquivos abertos direto do computador. Nesse caso, abra a pasta no VS Code, instale a extensão **Live Server** e clique em "Go Live".
