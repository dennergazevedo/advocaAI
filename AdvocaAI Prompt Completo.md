# 🏛️ Prompt: Landing Page — AdvocaAI

> **Objetivo:** Gerar uma landing page completa, profissional e otimizada para SEO para o escritório de advocacia **AdvocaAI**, com copy persuasiva, estrutura de seções estratégica e identidade visual que transmite autoridade, confiança e modernidade.

---

## 🎨 IDENTIDADE VISUAL & DIRETRIZ ESTÉTICA

### Paleta de Cores
```
Primária    → #0A1628  (Azul-marinho profundo — autoridade e seriedade)
Secundária  → #C9A84C  (Dourado envelhecido — prestígio e excelência)
Acento      → #1B3A6B  (Azul royal — confiança institucional)
Fundo       → #F5F1EB  (Off-white creme — elegância e limpeza)
Texto       → #1A1A1A  (Quase-preto — legibilidade máxima)
Destaque    → #E8D5A3  (Dourado claro — hover states e sublinhados)
```

### Tipografia
```
Display / Títulos → "Playfair Display" (serif, elegante, peso 700–900)
Corpo / Texto     → "DM Sans" (sans-serif limpo, peso 300–500)
Destaques/Legal   → "Cormorant Garamond" (refinamento jurídico, itálico)
```

### Estilo Estético
- **Tom:** Luxury Refined + Institutional Authority
- **Atmosfera:** Escritório de alto padrão, gabinetes de mogno, livros jurídicos, confiança inabalável
- **Texturas:** Papel pergaminho sutil no fundo, padrões geométricos em dourado, gradiente escuro nas seções hero
- **Animações:** Fade-in suave ao scroll, underline dourado animado nos títulos, hover com elevação discreta nos cards
- **Elemento Diferenciador:** Linha dourada vertical decorativa separando colunas; ícones de balança e coluna grega como elementos gráficos de apoio

---

## 🔍 ESTRATÉGIA SEO

### Meta Tags (incluir no `<head>`)
```html
<title>AdvocaAI | Advocacia Digital de Alta Performance</title>
<meta name="description" content="O escritório AdvocaAI une tecnologia de ponta à expertise jurídica para proteger seus direitos com agilidade, transparência e resultados comprovados. Consulta gratuita." />
<meta name="keywords" content="advocacia, advogado online, consultoria jurídica, direito digital, escritório de advocacia, AdvocaAI, advogado especialista" />
<meta property="og:title" content="AdvocaAI — Advocacia que trabalha por você" />
<meta property="og:description" content="Proteção jurídica inteligente. Atendimento humanizado. Resultados reais." />
<meta property="og:type" content="website" />
<meta name="robots" content="index, follow" />
<link rel="canonical" href="https://www.advocaai.com.br" />
```

### Schema Markup (JSON-LD)
```json
{
  "@context": "https://schema.org",
  "@type": "LegalService",
  "name": "AdvocaAI",
  "description": "Escritório de advocacia digital especializado em direito civil, trabalhista, empresarial e digital.",
  "url": "https://www.advocaai.com.br",
  "telephone": "+55-11-99999-0000",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "São Paulo",
    "addressRegion": "SP",
    "addressCountry": "BR"
  },
  "openingHours": "Mo-Fr 08:00-18:00",
  "priceRange": "$$",
  "hasOfferCatalog": {
    "@type": "OfferCatalog",
    "name": "Serviços Jurídicos AdvocaAI"
  }
}
```

### Estrutura de Headings SEO
```
H1 → Uma por página (no Hero)
H2 → Um por seção principal
H3 → Subsistemas dentro de cada seção
```

---

## 🗂️ ESTRUTURA DE SEÇÕES

### 1. `<HEADER>` — Navegação Fixo
**Elementos:**
- Logo: `AdvocaAI` em Playfair Display dourado + ícone de balança minimalista
- Menu: `Início | Serviços | Sobre Nós | Resultados | Blog | Contato`
- CTA no header: botão `→ Consulta Gratuita` (fundo dourado, texto escuro)
- Sticky com blur de fundo ao scroll (backdrop-filter)

---

### 2. `<HERO>` — Seção Principal

**Layout:** Full-screen dividido — esquerda texto / direita imagem editorial de advogado em escritório moderno (placeholder)

**Copy:**
```
[Supertítulo — pequeno, dourado, espaçado em maiúsculas]
ADVOCACIA COM INTELIGÊNCIA

[H1 — grande, Playfair Display, branco sobre fundo escuro]
Protegemos o que
é seu por direito.

[Subtítulo — DM Sans, peso 300, cinza-claro]
O AdvocaAI une tecnologia jurídica de ponta e
atendimento humano para defender seus interesses
com agilidade, precisão e total transparência.

[Botões CTA]
→ Falar com um Advogado Agora    [Primário — dourado]
→ Conheça Nossos Serviços        [Secundário — outline branco]

[Indicadores sociais abaixo dos CTAs]
✦ +1.200 casos resolvidos   ✦ 98% de satisfação   ✦ Atendimento em 24h
```

---

### 3. `<SOBRE>` — Quem Somos

**Layout:** Duas colunas — esquerda imagem institucional / direita texto com linha dourada vertical decorativa

**Copy (H2 + corpo):**
```
[H2]
Mais do que um escritório.
Somos seus parceiros jurídicos.

[Corpo — Cormorant Garamond, 18px, estilo editorial]
O AdvocaAI nasceu da convicção de que acesso à
justiça deve ser simples, transparente e eficiente.

Combinamos a solidez da advocacia tradicional com
ferramentas de inteligência jurídica para oferecer
estratégias mais rápidas, mais precisas e com
resultados mensuráveis para cada cliente.

Não somos apenas advogados. Somos guardiões dos
seus direitos — digitais e presenciais.

[Diferenciais em ícone + texto — 3 colunas]
⚖️ Ética acima de tudo
🛡️ Sigilo absoluto garantido
🤖 Tecnologia a serviço da justiça
```

---

### 4. `<SERVIÇOS>` — Áreas de Atuação

**Layout:** Grid 2×3 de cards com borda dourada, ícone, título e descrição curta + link

**Copy:**

```
[H2]
Nossas Áreas de Atuação

[Subtítulo]
Expertise jurídica especializada para cada etapa da sua vida.
```

**Cards:**

```
[Card 1] ⚖️ Direito Civil
Contratos, cobranças, responsabilidade civil, indenizações e
disputas entre particulares. Defendemos seus interesses com
estratégia e rapidez.
→ Saiba mais

[Card 2] 👔 Direito Trabalhista
Rescisões indevidas, horas extras, assédio moral e muito mais.
Trabalhamos para garantir que você receba o que merece.
→ Saiba mais

[Card 3] 🏢 Direito Empresarial
Abertura e encerramento de empresas, contratos comerciais,
societário e compliance. Protegemos seu negócio em cada etapa.
→ Saiba mais

[Card 4] 💻 Direito Digital
Crimes cibernéticos, proteção de dados (LGPD), contratos
digitais e reputação online. Navegue com segurança jurídica.
→ Saiba mais

[Card 5] 🏠 Direito Imobiliário
Compra, venda, locação, usucapião e regularização de imóveis.
Transações seguras do início ao fim.
→ Saiba mais

[Card 6] 👨‍👩‍👧 Direito de Família
Divórcio, guarda, pensão alimentícia, inventário e herança.
Cuidamos das questões mais delicadas com discrição e cuidado.
→ Saiba mais
```

---

### 5. `<PROCESSO>` — Como Trabalhamos

**Layout:** Timeline horizontal com 4 etapas e linha dourada conectora

**Copy:**
```
[H2]
Do problema à solução:
nosso processo transparente.

[Etapas]

① CONSULTA GRATUITA
Entendemos seu caso em uma primeira conversa
sem compromisso, presencial ou online.

② ANÁLISE ESTRATÉGICA
Nossos especialistas mapeiam os caminhos
jurídicos mais eficazes para sua situação.

③ AÇÃO COORDENADA
Executamos a estratégia com rigor técnico,
mantendo você informado em cada etapa.

④ RESULTADO GARANTIDO
Acompanhamos até a resolução final.
Seu sucesso é nossa vitória.
```

---

### 6. `<PROVA SOCIAL>` — Resultados & Depoimentos

**Layout:** Fundo escuro (#0A1628) com números em dourado + carrossel de depoimentos

**Copy — Números:**
```
[H2, branco]
Resultados que falam
por si mesmos.

1.200+          R$ 8M+           98%             15 anos
Casos           Recuperados      Aprovação        de Experiência
Resolvidos      para clientes    dos clientes
```

**Copy — Depoimentos:**
```
[Card depoimento 1]
"O AdvocaAI me ajudou a recuperar tudo que era meu por
direito trabalhista. Processo rápido, comunicação clara
e resultado acima do esperado."
— Mariana R., São Paulo

[Card depoimento 2]
"Finalmente um escritório que explica tudo em português!
Meu processo de divórcio foi conduzido com muita
sensibilidade e profissionalismo."
— Carlos M., Campinas

[Card depoimento 3]
"Eles salvaram minha empresa de uma disputa societária
complexa. Estratégia brilhante e total dedicação."
— Fernanda L., Rio de Janeiro
```

---

### 7. `<FAQ>` — Perguntas Frequentes

**Layout:** Accordion elegante com linha divisória dourada

**Copy (H2 + perguntas):**
```
[H2]
Dúvidas frequentes

[Perguntas]
→ A primeira consulta realmente é gratuita?
Sim. Nossa consulta inicial é 100% gratuita e sem compromisso.
Queremos entender seu caso antes de qualquer decisão.

→ Preciso comparecer ao escritório pessoalmente?
Não necessariamente. Atendemos de forma 100% digital para a
maioria dos casos, com total segurança e validade jurídica.

→ Como funciona o pagamento pelos serviços?
Trabalhamos com honorários fixos, êxito ou mensalidade,
dependendo do tipo de serviço. Tudo transparente antes de começar.

→ Vocês atendem pessoa jurídica?
Sim. Temos equipe especializada em direito empresarial para
startups, PMEs e grandes empresas.

→ Em quanto tempo terei retorno após entrar em contato?
Nosso compromisso é responder em até 24 horas úteis.
```

---

### 8. `<CTA FINAL>` — Seção de Conversão

**Layout:** Full-width, fundo com textura dourada/marinho, texto centralizado, formulário simples

**Copy:**
```
[H2 — grande, Playfair Display]
Seu direito não pode esperar.

[Subtítulo]
Converse com um especialista AdvocaAI hoje mesmo.
Sem burocracia. Sem jargões. Sem custo inicial.

[Formulário inline]
[Nome completo]   [E-mail]   [Área de interesse ▼]   [→ Quero minha consulta grátis]

[Selos de confiança abaixo do formulário]
🔒 Seus dados estão protegidos pela LGPD
⭐ Avaliação 4.9 no Google
✓ OAB Registrado
```

---

### 9. `<FOOTER>` — Rodapé

**Layout:** 4 colunas sobre fundo #0A1628

**Copy:**
```
[Coluna 1 — Logo e tagline]
AdvocaAI ⚖️
Advocacia inteligente, resultados reais.

[Coluna 2 — Links rápidos]
Início | Serviços | Sobre nós
Resultados | Blog | Contato

[Coluna 3 — Contato]
📍 Av. Paulista, 1000 — São Paulo, SP
📞 (11) 99999-0000
✉️ contato@advocaai.com.br
🕐 Seg–Sex, 8h às 18h

[Coluna 4 — Redes sociais + Newsletter]
Siga o AdvocaAI:
[Instagram] [LinkedIn] [YouTube]

Receba dicas jurídicas:
[E-mail _____] [→ Assinar]

[Linha final]
© 2025 AdvocaAI. Todos os direitos reservados.
OAB/SP XXXXXX | Política de Privacidade | Termos de Uso
```

---

## ⚙️ INSTRUÇÕES TÉCNICAS PARA O CLAUDE DESIGN

```
Ao renderizar esta landing page, siga estas diretrizes:

1. FRAMEWORK: HTML puro com CSS custom properties + JS vanilla.
   Alternativa: React com Tailwind (sem componentes genéricos de UI).

2. ANIMAÇÕES:
   - Fade-in + translate-Y ao entrar no viewport (IntersectionObserver)
   - Underline dourado animado nos H2 (pseudo-elemento ::after)
   - Cards com transform: translateY(-4px) e box-shadow dourado no hover
   - Números na seção de resultados com efeito de contagem animada

3. RESPONSIVIDADE:
   - Mobile-first obrigatório
   - Breakpoints: 480px / 768px / 1024px / 1440px
   - Menu hambúrguer no mobile com slide-in lateral
   - Cards em coluna única no mobile

4. PERFORMANCE & SEO:
   - Imagens com atributo alt descritivo
   - Lazy loading nas imagens abaixo do fold
   - Fonte carregada via Google Fonts com preconnect
   - Semântica HTML5 rigorosa (nav, main, section, article, aside, footer)

5. ACESSIBILIDADE:
   - Contraste mínimo AA (WCAG 2.1)
   - Focus visible em todos os elementos interativos
   - ARIA labels no menu mobile e accordion

6. ELEMENTOS VISUAIS:
   - Usar SVG inline para ícones (balança, escudo, digital, etc.)
   - Fundo hero: gradiente diagonal de #0A1628 para #1B3A6B
   - Separadores de seção: linha dourada de 2px ou elemento decorativo geométrico
   - Badge "Consulta Grátis" flutuante no canto inferior direito (fixed)
```

---

## 📋 CHECKLIST FINAL

- [ ] Logo AdvocaAI visível e clicável no header
- [ ] CTA de consulta gratuita em pelo menos 3 pontos da página
- [ ] Número de WhatsApp linkado com `wa.me/`
- [ ] Formulário de contato funcional (ou integrado com Formspree)
- [ ] Google Analytics / Meta Pixel configurados
- [ ] Sitemap.xml gerado
- [ ] robots.txt configurado
- [ ] Certificado SSL ativo
- [ ] Open Graph tags para compartilhamento social
- [ ] Schema markup LegalService implementado
- [ ] Página carregando em < 3s (Core Web Vitals)

---

> **Nota para o designer/dev:** Este prompt deve ser tratado como briefing completo.
> Toda copy está pronta para uso direto. Adapte apenas dados reais (telefone, endereço, OAB).
> Mantenha a hierarquia visual: **Azul-marinho → Dourado → Branco** como tríade dominante.
