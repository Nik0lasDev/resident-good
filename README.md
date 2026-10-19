# Resident Good — Protótipo FPS

Protótipo inicial de combate em primeira pessoa para validar o esqueleto do jogo no navegador.

## O que já funciona

- Cenário 3D de treinamento com iluminação, paredes e marcações no piso.
- Câmera em primeira pessoa com mouse e movimentação WASD.
- Pistola 3D simples visível na câmera.
- Disparo por clique esquerdo, mira central e feedback de acerto.
- Carregador de 12 disparos, 48 munições de reserva e recarga pela tecla **R**.
- Alvo de treino parado com 100 HP, barra de vida e dano de 10 por tiro.
- Reinício do alvo depois de neutralizá-lo.

## Como executar

O projeto usa Three.js por CDN e módulos JavaScript, então abra a página por um servidor HTTP local (não diretamente como arquivo `file://`).

### Opção 1 — VS Code / Cursor

1. Clone ou baixe este repositório.
2. Abra a pasta no Cursor ou VS Code.
3. Inicie um servidor local na pasta raiz (por exemplo, com a extensão Live Server).
4. Abra o endereço local fornecido pelo servidor.

### Opção 2 — Python

Com Python instalado, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

## Controles

| Ação | Controle |
| --- | --- |
| Entrar no teste / capturar mouse | Botão **Entrar no teste** |
| Olhar | Mouse |
| Mover | **W A S D** |
| Correr | **Shift** |
| Atirar | Clique esquerdo |
| Recarregar | **R** |
| Liberar o mouse | **Esc** |

## Observações técnicas

- Não há etapa de build nem dependências locais; o Three.js é carregado do jsDelivr.
- É necessária conexão com a internet para carregar o módulo Three.js.
- O teste foi pensado para teclado e mouse em desktop; controles touch ainda não estão implementados.
- Esta é uma base de protótipo, não uma versão final de jogo: não inclui IA inimiga, áudio, animações completas, salvamento ou sistema de níveis.
