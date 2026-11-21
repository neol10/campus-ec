# NEWNEO Web Architect — Estado do Projeto

**Projeto:** Barbearia Campus  
**Direção Criativa:** Campus Street Barber (Streetwear Editorial / Brutalismo Refinado)  
**Repositório:** `neol10/campus-ec` (branch `main`)  
**Data da Última Atualização:** 20/11/2026  

---

## 1. Contexto e Stack
- **Framework:** HTML5 semântico nativo + CSS3 modular (`:root` tokens) + JavaScript Vanilla.
- **Animação:** GSAP 3.12.5 + ScrollTrigger via CDN.
- **Fontes Ativas:** `Barlow Condensed` (Street Display) + `Plus Jakarta Sans` (Interface / Street Sans) + `Cormorant Garamond` (Legado preservado onde aplicável).
- **Mídia:** Vídeos Full HD 1080p FastStart (`hero.mp4`, `cinematic-scroll-optimized.mp4`) e fotografias reais em alta resolução (`assets/img/`).

---

## 2. Status das Etapas (Roadmap de Redesign)

| Etapa | Nome da Etapa | Status | Detalhes e Entregáveis |
| :--- | :--- | :--- | :--- |
| **Etapa 1** | Auditoria e Planejamento de Redesign | `APROVADA` | Diagnóstico de arquitetura, inventário de mídias e plano de 7 etapas aprovados pelo usuário. |
| **Etapa 2** | Design System Street Barber + Header | `APROVADA` | Tokens CSS semânticos criados, nova logo textual `CAMPUS.`, Header desktop e mobile redesenhados em alto contraste. |
| **Etapa 3** | Novo Hero Street Barber | `APROVADA` | Hero editorial full-screen brutalista com headline titânica `CORTE. ATITUDE. IDENTIDADE.`, vídeo/foto de fundo e CTAs de alto contraste. |
| **Etapa 4** | Seção Institucional & Serviços | `APROVADA` | Seção "A Barbearia" (`#sobre`) e "Serviços" (`#servicos`) redesenhadas no estilo Street Barber com `data-svc` preservados. |
| **Etapa 5** | Galeria, O Espaço & Localização | `APROVADA` | Galeria editorial com fotos reais e lightbox (`#galeria`), O Espaço arquitetônico com alternância de ritmo (`#espaco`) e Localização com CTA "Como Chegar" e dados comerciais (`#contato`). |
| **Etapa 6** | Responsividade, Animações & Refinamento | `APROVADA` | Polimento mobile (320px a 768px), remoção do CTA redundante do topo mobile, calibração da velocidade do Cinematic Scroll (`end: +=900%` mobile / `+=1100%` desktop), erradicação do azul legado e fix do favicon.ico. |
| **Ajustes Pontuais** | Hero Mobile + CTAs Dourados + Desobstrução CTA Flutuante | `APROVADA` | Rebalanceamento vertical do Hero mobile; botões dourados sólidos (`#D4AF37`) nos três serviços; desobstrução do botão flutuante em `#servicos` e `#agendamento`. |
| **Hero Mobile 2.0** | Refinamento Visual Tipográfico e Hierarquia Editorial | `APROVADA` | Hierarquia editorial: `CORTE` e `ATITUDE` em branco sólido Barlow 800; `IDENTIDADE.` em Vermelho Street (`#D91F3C`); overlay direcional localizado. |
| **Alinhamento do Hero** | Calibração do Recuo Horizontal do Container do Hero | `APROVADA` | Ajuste exclusivo em `.hero-street-container`: Desktop (>= 1024px) com 48px a 64px; Tablet (768px a 1023px) com 32px a 40px; Mobile (até 767px) com 20px a 24px. Alinhamento rigoroso entre etiqueta, título, subtítulo e CTAs. |
| **Agendamento Express** | Reformulação Compacta, Mobile First & CTAs Dourados | `CONCLUIDO` | Layout centralizado compacto em card único (max 680px), headline "AGENDE SEU CORTE." (Barlow 800), chips ativos com destaque dourado (#D4AF37), horários em `<details>` colapsável, confirmação em 1 linha, preview visual oculto, botão CTA dourado sólido, 100% das regras e WhatsApp mantidos. |
| **Etapa 7** | Auditoria Final e Publicação | `PLANEJADA` | Checklist final de regressão, métricas de performance, SEO, acessibilidade e publicação. |

---

## 3. Áreas Congeladas e Funcionalidades Preservadas
- [x] Header Street Barber com Menu toggle mobile simplificado e CTA desktop preservado.
- [x] Hero Desktop e Mobile com novo recuo horizontal editorial e alinhamento perfeito.
- [x] Seção A Barbearia intacta com fotos reais e ritmo editorial.
- [x] Seção Serviços com botões dourados editoriais de alto contraste e atributos `data-svc` preservados.
- [x] Botão flutuante mobile de agendamento com desobstrução inteligente via `IntersectionObserver` em `#servicos` e `#agendamento`.
- [x] Galeria, O Espaço e Localização em alto contraste com fotos reais da barbearia.
- [x] Lógica de agendamento multi-profissional no WhatsApp (Tavares, Gleidson, Diego) com pré-seleção por `data-svc`.
- [x] Regras de calendário (bloqueio de sábados e datas retroativas) e períodos dinâmicos de atendimento.
- [x] Motor do Cinematic Scroll (seek reativo bidirecional com `pendingSeekTime`, `scrub: 0.85` e extensão calculada de rolagem).
- [x] Dados comerciais, horários e endereço preservados.

---

## 4. Próximo Passo
Aguardar aprovação explícita do usuário da **Reformulação — Agendamento Express** para prosseguir com os próximos passos ou com a **Etapa 7: Auditoria Final e Publicação**.
