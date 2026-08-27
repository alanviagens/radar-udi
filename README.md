# Radar UDI 2.0 — SerpApi + Google Flights

REC, MCZ e JPA → UDI, 20–22/12/2026. Atualização automática em 30 ou 60 minutos, preço-alvo e PWA.

## Configuração
1. Copie `.env.example` para `.env`.
2. Coloque sua chave SerpApi em `SERPAPI_KEY`.
3. `npm install`
4. `npm start`
5. Abra `http://localhost:3000`.

A chave fica somente no backend. O radar usa uma consulta por data com as três origens para reduzir chamadas. A SerpApi permite filtros/ordenação de Google Flights e informa que buscas em cache por até 1 hora não consomem créditos.
