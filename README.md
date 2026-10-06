# MespreX Bio — Painéis grátis

Site público independente da MespreX para divulgar painéis gratuitos. Cada card pode exibir a imagem de demonstração do painel e leva ao link de acesso. Ele lê os itens publicados pelo painel através de `GET /api/buttons`.

Quando os dois sites estiverem no mesmo domínio, mantenha `window.MESPREX_API_BASE = ''` em `config.js`. Se a bio estiver hospedada em outro endereço, coloque em `config.js` a URL base do servidor que expõe a API, sem uma barra no final.

A versão do projeto Manus já tem a API integrada em `/api/buttons` e os dados persistidos no banco gerenciado. Firebase não é necessário nesta versão.
