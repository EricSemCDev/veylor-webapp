# One-Pager — Veylor Web

## Nome + one-liner
**Veylor Web** — Ferramentas unificadas para criar, gerenciar e jogar campanhas de RPG de mesa online  
*(Problema: falta de centralização e interatividade; Solução: plataforma única e imersiva; Público: mestres e jogadores).*

---

## Objetivo geral
Entregar uma aplicação web funcional que centralize campanha, fichas e rolagens, melhorando organização e imersão nas mesas de RPG.

### Objetivos específicos
1. Permitir **cadastro/login** e gerenciamento de **campanhas**.  
2. Oferecer **fichas de personagem** com registro de status, buffs/debuffs e anotações.  
3. Disponibilizar **rolagens/dados** e **inventário/itens** integrados ao fluxo de jogo.

---

## Escopo

### IN (versão Demo Day)
- Autenticação e perfis básicos.  
- Campanhas (criar/gerenciar) e **agenda** de sessões.  
- **Fichas** (HP/status, buffs/debuffs, anotações) e organização de habilidades.  
- **Inventário/itens** (peso, descrição, empréstimos).  
- **Inimigos/bestiário** do mestre.  
- **Ferramenta de dados** e rolagens personalizáveis.  
- **Mapa-múndi** navegável do universo da campanha.

### OUT (pós-Demo Day)
- Chat de voz/integração Discord e mensagens privadas.  
- Modo claro/escuro e personalização de perfil/favoritos.  
- Dashboards de estatísticas e **iniciativa/combate** avançado.  
- Música/ambientação e integração com outros sistemas (D&D etc.).  
- App mobile nativo e compartilhamento de conteúdos.

---

## Métricas de sucesso (SMART)
1. **Deploy público ativo** no Demo Day com **≥95% de uptime** na semana da apresentação.  
2. **4 fluxos E2E** funcionando até o Demo Day: (i) cadastro/login, (ii) criar campanha, (iii) criar personagem, (iv) rolagem registrada na ficha.  
3. **Tempo mediano da API < 400 ms** para CRUD de ficha/itens em ambiente de demonstração.  
4. **Pipeline CI rodando testes a cada PR na main** e **≥15 testes** (unitários/integrados) antes do Demo Day.

---

## Stack prevista
- **Frontend:** React (Next.js ou Vite) + Tailwind
- **Backend:** Node.js (Express)  
- **Banco:** PostgreSQL  
- **Deploy:** Frontend em Vercel e Backend em Render (Postgres persistente)  
- **CI/CD:** GitHub Actions (build/test)  
- **UI/UX:** Figma para prototipação

---

## Por que este tema (motivação/valor)
Há carência de ferramentas realmente **personalizáveis e interativas** para gestão de campanhas.  
O Veylor propõe **unificar** fichas, rolagens, bestiário, inventário e mapas em uma experiência só, elevando a **organização e imersão** de mestres e jogadores.
