# Changelog

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

## [1.2.0] - 2026-05-16
### Adicionado
- Sistema de **Persistência de Volume** via `localStorage`.
*   Arquivo `.gitignore` configurado para deploys no GitHub Pages.
*   Documentação inicial (`README.md`, `CHANGELOG.md`, `LICENSE`).

### Melhorado
*   **Otimização de Performance**: Refatoração completa do pool de partículas usando filtro in-place (O(n)).
*   **Correção de Freeze**: Resolvido o problema de congelamento de 5 segundos ao clicar em "Retry" através da sincronização do tempo de áudio.
*   **Gerenciamento de Memória**: Implementado reuso de objetos (Object Pooling) para partículas, reduzindo a pressão no Garbage Collector.

## [1.1.0] - 2026-05-15
### Adicionado
- Sistema de **Lyrics (Letras)** sincronizado com a música.
- Cache de renderização para textos para evitar stuttering.
- Controle de volume ("Sinfonia do Vazio") no menu inicial.
- Ranking Global integrado com Firebase Firestore.

### Corrigido
- Ajuste de tamanho de fonte dinâmico para diferentes resoluções.
- Correção na camada de renderização (letras agora ficam no background).

## [1.0.0] - 2026-05-10
### Adicionado
- Lançamento inicial do Void Despair.
- Mecânicas básicas de movimento, escudo e projéteis.
- Inimigos (Shooters) e Projéteis Pesados.
- Power-ups de recarga e pulso.
