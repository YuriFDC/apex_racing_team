# Apex GP — Racing Team Landing Page

> Design system completo para uma equipe fictícia de Fórmula 1, construído com HTML, CSS e JavaScript puro — sem frameworks.

---

## Visão geral

Este projeto nasceu como um exercício de design system aplicado a uma landing page de alta fidelidade. O desafio foi criar uma identidade visual coesa, com animações funcionais e hierarquia de informação clara, usando apenas tecnologias nativas do browser.

O resultado é um arquivo HTML único, totalmente autossuficiente, com imagens embutidas em base64 — sem dependência de CDN ou servidor externo para os assets.

---

## Decisões de design

**Tipografia em três camadas**
A escolha tipográfica foi pensada para criar hierarquia sem precisar de cor. `Barlow Condensed` cobre os títulos e displays — condensada, pesada, industrial. `Barlow` regular cuida do corpo de texto com boa legibilidade em telas pequenas. `Rajdhani` assume os labels técnicos, números de piloto e tags — ela tem um caráter mais "HUD" que combina com o universo motorsport.

**Paleta restrita e intencional**
Vermelho `#E8001A` e azul `#0057FF` refletem as iniciais destacadas do nome da equipe (A e R). O dourado `#C8A84B` aparece apenas na seção de pilotos, criando um momento de distinção sem poluir o sistema. O restante da paleta é quase monocromático — superfícies escuras em três níveis (`#0d0d0d`, `#141414`, `#1a1a1a`) que dão profundidade sem distrair.

**Grid de 1px como linguagem visual**
A separação entre blocos usa linhas de 1px em vez de espaço em branco. Essa escolha referencia o visual de dashboards de telemetria e scoreboards de transmissão de F1 — onde cada informação tem seu compartimento exato.

**Animações com propósito**
Cada animação tem uma função clara:
- O ticker vermelho no topo comunica "ao vivo", criando senso de urgência
- O scroll reveal com `translateY` guia a leitura verticalmente
- O `grayscale` nos cards de piloto que desaparece no hover reforça a ideia de "ativação"
- O contador animado nos stats transforma números estáticos em dados que "chegam"

**HTML único como decisão técnica**
Imagens convertidas para base64 e embutidas diretamente no HTML. Isso elimina requests extras, facilita o deploy (basta um arquivo) e garante que o projeto funciona offline — ideal para portfolio e apresentações.

---

## Tecnologias

- HTML5 semântico
- CSS custom properties (variáveis de design system)
- CSS animations e transitions nativas
- JavaScript vanilla — IntersectionObserver para scroll reveal, animação de contadores
- Google Fonts — Barlow Condensed, Barlow, Rajdhani



## Créditos das fotografias

Todas as imagens são de uso livre via [Unsplash](https://unsplash.com) e [Pexels](https://pexels.com).

| Imagem | Autor | Fonte |
|---|---|---|
| Carro preto dourado (hero) | Aman Pal | Unsplash |
| Dois carros na pista (tecnologia) | Philip Myrtorp | Unsplash |
| Capacete colorido — Moretti | Dayvidproductions | Pexels |
| Capacete P&B — Cole | Tima Miroshnichenko | Pexels |
| Ferrari na chuva | Jonathan Borba | Pexels |
| Silhueta ao pôr do sol | Mathias Dargnat | Unsplash |
| McLaren na curva | Jonathan Borba | Pexels |
| Pneus Pirelli | Jonathan Borba | Pexels |
| Pit lane Singapore | Anthony Lim | Unsplash |
| Red Bull em pista | Jonathan Borba | Pexels |
| Mônaco noite | Hudson McDonald | Pexels |

---

## Autor

Feito por Yuri (Castro Design).  
Entre em contato via [LinkedIn](https://www.linkedin.com/in/yuri-fernandes-admin/) ou [Instagram](https://www.instagram.com/yuricastro.design/).
