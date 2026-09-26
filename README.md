# Concord para Windows

Baixe a versão mais recente em [Releases](https://github.com/KevynMurilo/Concord-Downloads/releases/latest). Há um instalador para Windows 10/11 x64 e um executável portátil.

O Concord funciona na bandeja. Fechar a janela mantém a chamada ativa. Na primeira abertura, informe o endereço HTTPS do servidor fornecido pelo administrador da comunidade; o instalador não inclui endereço, IP ou senha.

## Na chamada

- Voz, chat temporário e compartilhamento de tela ou janela. O volume da transmissão é separado do volume das vozes.
- Medidor de captação local do microfone, sons opcionais de entrada, saída e início de transmissão, notificações e atalhos configuráveis.
- Pressionar para falar funciona enquanto a janela do Concord está em foco. Com um jogo em foco, o atalho global do microfone alterna transmissão e silêncio. A aba Atalhos mostra se cada combinação foi registrada; Ctrl+Insert é o padrão para abrir ou ocultar a janela. Jogos em tela cheia exclusiva podem bloquear atalhos do Windows.
- A qualidade automática reduz a captura em salas maiores. Há perfis de até 1080p/30 e 1080p/60 FPS para até três pessoas; os FPS reais dependem do computador e da rede.
- Transmissões recebidas podem abrir em tela cheia. A prévia da própria tela não é ampliada para evitar captura em loop; ao transmitir um monitor, a ampliação fica indisponível até parar ou trocar para uma janela.

O servidor guarda apenas metadados da sala em H2. Chat não tem histórico no servidor; voz e vídeo usam WebRTC direto entre participantes ou TURN quando necessário. Cada transmissor envia uma cópia por espectador, por isso grupos maiores exigem mais upload. Conteúdo protegido por DRM pode aparecer preto; o Concord não contorna essa proteção.

Os executáveis não têm assinatura digital comercial, então o Windows pode exibir um aviso de editor desconhecido. O código-fonte fica em um repositório privado.