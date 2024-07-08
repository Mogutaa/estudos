Explicação do HTML

head: Contém metadados do documento, como a codificação de caracteres e o link para o arquivo CSS.

body: Abriga o conteúdo principal da página. Aqui, temos uma estrutura de divs aninhadas que representam a moldura (frame), a tela (canvas) e três áreas coloridas (one, two e three).

Explicação do CSS

.canvas: Define a área da tela com um tamanho específico, uma cor de fundo e um efeito de desfoque para imitar a textura da pintura.

.frame: Cria uma moldura preta ao redor da tela, dando a impressão de um quadro.

.one, .two, .three: Essas classes representam as diferentes camadas de cor na pintura. Cada uma tem suas próprias dimensões, cores e efeitos de desfoque. O leve uso de transform: rotate adiciona um toque de autenticidade, simulando a imperfeição de pinceladas manuais.

Pontos Interessantes

Desfoque (filter: blur): Usar desfoque em diferentes níveis nas camadas adiciona profundidade e realismo à pintura.

Sombreamento (box-shadow): As sombras ao redor das cores ajudam a destacar cada seção, imitando a técnica de Rothko de criar contrastes suaves.

Transformações sutis (transform: rotate): Pequenas rotações em cada div adicionam uma sensação de movimento e organicidade.
