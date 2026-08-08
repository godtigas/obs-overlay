# TaydoDrill — OBS Overlay Kit

Conjunto de overlays para OBS usados na stream de slots/casino do **TaydoDrill** (canal Twitch: [oscolderst](https://www.twitch.tv/oscolderst)).

Tema visual: fundo animado "aurora" em tons de azul/ciano, com relogio, cronometro de sessao, ticker de crypto ao vivo (Binance) e toggle manual WAGER/RAW.

## Ficheiros

- `taydodrill_overlay.html` — barra do topo (logo, relogio, timer, crypto, toggle). 1920x1080.
- `taydodrill_chat_topright.html` — chat da Twitch, canto superior direito. 1920x1080.
- `taydodrill_starting_soon.html` — ecra "a stream comeca em breve" com contagem decrescente. 1920x1080.

## Como usar no OBS

Adiciona uma Browser Source e usa o link direto (nao "Local file"), para os ficheiros se atualizarem sozinhos sempre que houver um push novo:

- https://godtigas.github.io/obs-overlay/taydodrill_overlay.html
- https://godtigas.github.io/obs-overlay/taydodrill_chat_topright.html
- https://godtigas.github.io/obs-overlay/taydodrill_starting_soon.html

Cada overlay verifica de 20 em 20 segundos se o proprio ficheiro mudou no GitHub e recarrega-se sozinho quando ha uma atualizacao.
