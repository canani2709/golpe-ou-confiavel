# Fontes das mídias do jogo

## Imagens atuais: todas inventadas

As 8 imagens em `midia/` foram **criadas para o jogo** em 26/10/2026. Não são prints de anúncios reais: não mostram pessoas reais (só silhuetas sem rosto), marcas reais, QR codes, chaves Pix, telefones nem links. No jogo, todas continuam com a marca "reconstituição".

| Caso | Arquivo | Baseado em |
|---|---|---|
| 1 · Bônus Brasil Oficial | `01-bonus.png` | caso noticiado (Tecnoblog) |
| 2 · Loja Ventania | `02-loja.png` | anúncio legítimo inventado |
| 3 · Promo Restaurantes BR | `03-restaurante.png` | caso noticiado (Mais Goiás) |
| 4 · Páscoa Premiada | `04-pascoa.png` | caso noticiado (Canaltech) |
| 5 · Festival Sertão Livre | `05-festival.png` | anúncio legítimo inventado |
| 6 · Ingressos Rock Shows | `06-ingresso.png` | caso noticiado (Jornal de Brasília) |
| 7 · Eventos BR Tickets | `07-turne.png` | caso noticiado (Canaltech) |
| 8 · Libera Brasil Gov | `08-programa.png` | caso noticiado (Olhar Digital) |

A fonte das artes (HTML) está em `.playwright-mcp/gerar-artes.html`.

## Para trocar por print de anúncio real

Na lista `MIDIA` do jogo, use `{ src: "midia/arquivo.png", real: true }`. A etiqueta muda para "Anúncio real" e a marca "reconstituição" some. Registre aqui: caso, arquivo, link na Biblioteca de Anúncios, página, data de criação da página, veiculação e data do print.

## Busca de 26/10/2026

**Caso 8: "Libera Brasil" e "Desenrola"**

- A página **Libera Brasil** tem anúncios que juntam vários sinais de golpe: nome de programa inexistente, link exibido como `WWW.SERASA.COM.BR` ou `CONEXAO-SEGURA.COM`, várias versões, anúncios de poucas horas. Um deles foi removido pela Meta ("não seguiu nossos Padrões de Publicidade").
  - [1642018037715407](https://www.facebook.com/ads/library/?id=1642018037715407) · 24/10/2026, ativo por 3 h
  - [2213133892952889](https://www.facebook.com/ads/library/?id=2213133892952889) · 25/10/2026, ativo por 22 h, link CONEXAO-SEGURA.COM
  - [1854870392176583](https://www.facebook.com/ads/library/?id=1854870392176583) · 11 a 17/10/2026, **removido pela Meta**
  - Páginas com nome de pessoa no mesmo esquema ("Marcos Vinicius", "Sabrina Oliveira"), link exibido como SERASA.COM.BR
  - **Por que não foram usados:** todos são vídeos com rosto identificável (simulação de telejornal, homem falando para a câmera). A busca filtrada só por imagem retornou 0 resultados.
  - **Opção sem rosto:** o cartão do anúncio 1854870392176583 mostra só a página "Libera Brasil" e o aviso de remoção da Meta. Não é o anúncio em si, mas pode servir como material de aula.
- "Desenrola" e "Desenrola Brasil" retornaram anúncios legítimos (governo, candidatos, bancos, livros).

**Casos 6 e 7: "pré-venda ingressos", "ingressos esgotados", "turnê Brasil ingressos"**

- A maioria dos resultados é de ticketeiras e produtoras conhecidas (Ticketmaster/Live Nation, Sympla, Q2 Ingressos, Bilheteria Digital) ou de bancos com pré-venda para clientes.
- **BuyTicket** ([1397767161887918](https://www.facebook.com/ads/library/?id=1397767161887918), cerca de 35 anúncios sobre o Iron Maiden): descartado. É uma plataforma de revenda já estabelecida (@buyticketbrasil, cerca de 144 mil seguidores), sem pagamento só por Pix e sem se passar por outra marca.
- **Velox Tickets** ([2035496200468006](https://www.facebook.com/ads/library/?id=2035496200468006)): descartado. Venda de ingresso de cinema, sem sinais de golpe.
- Observação: a biblioteca ordena por impressões, e anúncios de golpe costumam durar poucas horas e alcançar pouca gente. Por isso eles quase não aparecem nessas buscas genéricas.
