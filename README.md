# Concord para Windows

**Versão atual:** [1.3.12](https://github.com/KevynMurilo/Concord-Downloads/releases/tag/v1.3.12).

Baixe a versão mais recente em [Releases](https://github.com/KevynMurilo/Concord-Downloads/releases/latest). Há um instalador para Windows 10/11 x64 e um executável portátil. Ao terminar a instalação, o instalador oferece abrir o Concord.

O Concord funciona na bandeja. Fechar a janela mantém a chamada ativa. Na primeira abertura, informe o endereço HTTPS do servidor fornecido pelo administrador da comunidade; o instalador não inclui endereço, IP ou senha.

## Atualizações

A partir do instalador 1.3.9, o Concord procura novas versões ao abrir e a cada seis horas. Quando houver uma nova release, o aplicativo mostra um aviso na bandeja. Você escolhe quando baixar e quando reiniciar para instalar; o progresso aparece em **Configurações > Aplicativo**. O programa não encerra uma chamada sem sua confirmação.

Quem já usa **1.3.8 ou anterior precisa instalar 1.3.9 manualmente uma vez**, pois essas versões não possuem atualizador. O EXE portátil continua com atualização manual. Para cada nova versão funcionar no atualizador, a release precisa trazer o instalador e o arquivo `latest.yml` correspondente. O instalador ainda não tem assinatura digital comercial.
## Na chamada

- Em Configurações > Áudio, **Testar microfone** mostra a captação local sem gravar ou enviar voz; **Ouvir toque** testa a saída escolhida. Use fones durante chamadas para evitar retorno do toque.

- Câmera independente da tela: você pode ligar uma, outra ou ambas. Em grupos maiores, o app reduz a qualidade para poupar upload.
- O seletor abre em **Janelas**. Ao fechar a janela escolhida, a transmissão termina. **Tela inteira** pode mostrar outras janelas e notificações no mesmo monitor. O áudio do sistema começa desligado e só entra se você marcar a opção.
- A sobreposição tem canto e monitor configuráveis. Jogos em tela cheia exclusiva ou com anti-cheat podem ocultá-la; experimente modo janela sem bordas.
- Voz, chat temporário e compartilhamento de tela ou janela. O chat abre dentro da sala, com Voltar à sala e controles de voz acessíveis; não há exportação de conversa. O volume da transmissão é separado do volume das vozes.
- Medidor de captação local do microfone, sons opcionais de entrada, saída e início de transmissão, notificações e atalhos configuráveis.
- Pressionar para falar funciona enquanto a janela do Concord está em foco. Com um jogo em foco, o atalho global do microfone alterna transmissão e silêncio. A aba Atalhos mostra se cada combinação foi registrada; Ctrl+Insert é o padrão para abrir ou ocultar a janela. Jogos em tela cheia exclusiva podem bloquear atalhos do Windows.
- A qualidade automática reduz a captura em salas maiores. Há perfis de até 1080p/30 e 1080p/60 FPS para até três pessoas; os FPS reais dependem do computador e da rede.
- Transmissões recebidas podem abrir em tela cheia. A prévia da própria tela não é ampliada para evitar captura em loop; ao transmitir um monitor, a ampliação fica indisponível até parar ou trocar para uma janela.

O servidor guarda apenas metadados da sala em H2. Chat não tem histórico no servidor; voz e vídeo usam WebRTC direto entre participantes ou TURN quando necessário. Cada transmissor envia uma cópia por espectador, por isso grupos maiores exigem mais upload. Conteúdo protegido por DRM pode aparecer preto; o Concord não contorna essa proteção.

Os executáveis não têm assinatura digital comercial, então o Windows pode exibir um aviso de editor desconhecido. O código-fonte fica em um repositório privado.