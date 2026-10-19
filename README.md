<!--
  Resident Good · README do projeto
  O site do jogo é publicado pelo GitHub Pages.
-->

<div align="center">

# 🟠 RESIDENT GOOD

### Protótipo FPS · Campo de treinamento

Um teste jogável em primeira pessoa, direto no navegador.

[**▶ JOGAR NO NAVEGADOR**](https://nik0lasdev.github.io/resident-good/)

<br />

![Status](https://img.shields.io/badge/status-prot%C3%B3tipo-orange?style=for-the-badge)
![Plataforma](https://img.shields.io/badge/plataforma-navegador-blue?style=for-the-badge)
![Three.js](https://img.shields.io/badge/3D-Three.js-black?style=for-the-badge)

</div>

---

## 🎮 Sobre o jogo

Entre no campo de treinamento, equipe a pistola e teste sua mira contra um alvo estático. Esta é a primeira versão jogável do **Resident Good**, criada para validar os fundamentos do combate em primeira pessoa.

### O que você pode fazer

- **Explorar o cenário:** mova-se e olhe livremente em primeira pessoa.
- **Atirar:** dispare com a pistola e acompanhe o feedback de acerto.
- **Recarregar:** use a tecla `R` para trocar o carregador.
- **Testar o alvo:** reduza a vida do manequim até neutralizá-lo e continue o exercício.

## 🕹️ Controles

| Ação | Tecla / comando |
|:--|:--|
| Iniciar | Clique em **Entrar no teste** |
| Olhar ao redor | Mover o mouse |
| Movimentar | `W` `A` `S` `D` |
| Correr | `Shift` |
| Atirar | Clique esquerdo |
| Recarregar | `R` |
| Liberar o mouse | `Esc` |

## 🎯 Equipamento e alvo

<div align="center">

| Pistola | Alvo de treinamento |
|:--:|:--:|
| **12** tiros por carregador | **100 HP** de vida |
| **48** tiros de reserva | **10** de dano por tiro |
| Recarga temporizada | Alvo parado |

</div>

## 🚀 Como jogar

1. Abra **[Resident Good — Jogar agora](https://nik0lasdev.github.io/resident-good/)**.
2. Aguarde o carregamento do cenário 3D.
3. Clique em **Entrar no teste** para capturar o mouse.
4. Use os controles acima para movimentar, mirar, atirar e recarregar.

> **Se o jogo ainda não abrir:** o primeiro deploy do GitHub Pages pode precisar ser ativado nas configurações do repositório. Consulte [Configurar o GitHub Pages](https://github.com/Nik0lasDev/resident-good/settings/pages) e selecione **GitHub Actions** como fonte de publicação. Depois, acompanhe a execução em [Actions](https://github.com/Nik0lasDev/resident-good/actions).

## 🧰 Sobre este protótipo

- **Tecnologia:** HTML, CSS, JavaScript e Three.js.
- **Execução:** navegador moderno com WebGL e conexão à internet.
- **Build:** não é necessário instalar dependências nem compilar o projeto.
- **Plataforma testada como alvo:** computador com teclado e mouse. Controles de toque para celular ainda não estão implementados.

## 🛠️ Executar localmente

Se quiser executar ou modificar o projeto no seu computador:

```bash
git clone https://github.com/Nik0lasDev/resident-good.git
cd resident-good
python -m http.server 8000
```

Abra [http://localhost:8000](http://localhost:8000).

É necessário usar um servidor HTTP local porque o jogo carrega o Three.js como módulo JavaScript.

## 🗺️ Próximos passos

- [ ] Melhorar os modelos e as animações da arma.
- [ ] Adicionar áudio de disparo e recarga.
- [ ] Criar inimigos com comportamento e reação ao jogador.
- [ ] Implementar controles touch para dispositivos móveis.
- [ ] Expandir o campo de treinamento e adicionar objetivos.

---

<div align="center">

**Resident Good** · Protótipo em desenvolvimento

[Jogar](https://nik0lasdev.github.io/resident-good/) · [Código-fonte](https://github.com/Nik0lasDev/resident-good) · [Reportar problema](https://github.com/Nik0lasDev/resident-good/issues)

</div>
