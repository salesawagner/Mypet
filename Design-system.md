# MeuPetVida Design System

**VersÃ£o:** 1.0  
**Data:** Junho 2025  
**PÃºblico-alvo:** Donos de pets no Brasil (jovens adultos e famÃ­lias)

## VisÃ£o Geral

O MeuPetVida Design System Ã© um sistema de design completo e acessÃ­vel, criado especificamente para aplicativos mÃ³veis voltados ao cuidado e gerenciamento da vida dos pets. O sistema transmite confianÃ§a, cuidado e carinho, utilizando uma estÃ©tica clean e flat design otimizada para dispositivos mÃ³veis.

### PrincÃ­pios de Design

- **Acessibilidade em Primeiro Lugar**: Conformidade com WCAG 2.2 AA
- **Mobile-First**: Otimizado para iOS e Android
- **ConsistÃªncia**: PadrÃµes visuais uniformes em toda a aplicaÃ§Ã£o
- **Usabilidade**: Interface intuitiva e amigÃ¡vel
- **Escalabilidade**: Sistema flexÃ­vel que cresce com o produto

## Paleta de Cores

### Cores PrimÃ¡rias
- **Primary Blue** (#4A90E2): BotÃµes primÃ¡rios, headers, elementos de destaque
- **Primary Green** (#7ED321): AÃ§Ãµes positivas, confirmaÃ§Ãµes, saÃºde
- **Primary Beige** (#F5F5DC): Backgrounds, Ã¡reas de conteÃºdo neutro

### Cores SecundÃ¡rias
- **Secondary Blue** (#6BB6FF): Hover states, elementos interativos
- **Secondary Green** (#A8E657): Elementos de suporte, Ã­cones
- **Warm Gray** (#8E8E93): Texto secundÃ¡rio, elementos desabilitados

### Cores Neutras
- **White** (#FFFFFF): Backgrounds, cards, Ã¡reas de conteÃºdo
- **Light Gray** (#F2F2F7): Backgrounds alternativos, separadores
- **Medium Gray** (#C7C7CC): Borders, divisÃ³rias
- **Dark Gray** (#3A3A3C): Texto principal, tÃ­tulos
- **Black** (#000000): Texto de alta importÃ¢ncia, Ã­cones

### Cores de Alerta
- **Success Green** (#34C759): Mensagens de sucesso, confirmaÃ§Ãµes
- **Warning Orange** (#FF9500): Avisos, atenÃ§Ã£o necessÃ¡ria
- **Error Red** (#FF3B30): Erros, aÃ§Ãµes destrutivas
- **Info Blue** (#007AFF): InformaÃ§Ãµes, links

### Cores TemÃ¡ticas Pet
- **Paw Brown** (#8B4513): Elementos relacionados a pets, Ã­cones de patas
- **Soft Orange** (#FFB366): Elementos amigÃ¡veis, relacionados Ã  felicidade
- **Mint Green** (#98E4D6): Elementos de cuidado, bem-estar

### Dark Mode
- **Primary Blue Dark** (#0A84FF): VersÃ£o dark mode do azul primÃ¡rio
- **Primary Green Dark** (#30D158): VersÃ£o dark mode do verde primÃ¡rio
- **Background Dark** (#1C1C1E): Background principal dark mode
- **Card Background Dark** (#2C2C2E): Cards e containers em dark mode

## Tipografia

### FamÃ­lias de Fonte

#### Fonte Principal: Inter (Google Fonts)
**Uso:** Texto geral, interface, componentes  
**RazÃ£o:** Excelente legibilidade em mobile, suporte completo Ã  acessibilidade, ampla gama de pesos

#### Fonte SecundÃ¡ria: Nunito (Google Fonts)
**Uso:** Elementos amigÃ¡veis, tÃ­tulos especÃ­ficos  
**RazÃ£o:** Design amigÃ¡vel e arredondado, ideal para contexto de pets, boa legibilidade

#### Fonte MonoespaÃ§ada: JetBrains Mono (Google Fonts)
**Uso:** CÃ³digos, nÃºmeros de identificaÃ§Ã£o, dados tÃ©cnicos  
**RazÃ£o:** Clareza em dados numÃ©ricos e cÃ³digos

### Escala TipogrÃ¡fica

| Estilo | Tamanho | Line Height | Peso | Uso |
|--------|---------|-------------|------|-----|
| Display Large | 57px | 64px | Bold (700) | TÃ­tulos de onboarding, splash screens |
| Display Medium | 45px | 52px | Bold (700) | TÃ­tulos principais de tela |
| Headline Large | 32px | 40px | SemiBold (600) | TÃ­tulos de seÃ§Ãµes principais |
| Title Large | 22px | 28px | Medium (500) | TÃ­tulos de lista, navegaÃ§Ã£o |
| Body Large | 16px | 24px | Regular (400) | Texto principal, conteÃºdo |
| Body Medium | 14px | 20px | Regular (400) | Texto secundÃ¡rio, descriÃ§Ãµes |
| Label Large | 14px | 20px | Medium (500) | BotÃµes, tabs, labels |

### Regras de Acessibilidade

- **Tamanho mÃ­nimo:** 16px para texto principal
- **Contraste mÃ­nimo:** 4.5:1 para texto normal
- **Contraste para texto grande:** 3:1 para textos â‰¥18px
- **Line height:** 1.5x do font size
- **Comprimento de linha:** 35-45 caracteres mobile

## Sistema de Grid

### Breakpoints e Grid

| Breakpoint | Colunas | Margin | Gutter | Max Width |
|------------|---------|--------|--------|-----------|
| Mobile (320-480px) | 4 | 16px | 16px | 100% |
| Large Mobile (481-768px) | 4 | 20px | 16px | 100% |
| Tablet (769-1024px) | 8 | 32px | 16px | 100% |
| Desktop (1025px+) | 12 | 80px | 24px | 1200px |

### Sistema de EspaÃ§amento (8pt Grid)

| Token | Valor | Uso |
|-------|-------|-----|
| xs | 4px | EspaÃ§amento muito pequeno, elementos prÃ³ximos |
| sm | 8px | EspaÃ§amento pequeno, elementos relacionados |
| md | 16px | EspaÃ§amento padrÃ£o, entre componentes |
| lg | 24px | EspaÃ§amento grande, entre seÃ§Ãµes |
| xl | 32px | EspaÃ§amento muito grande, separaÃ§Ã£o importante |
| xxl | 48px | EspaÃ§amento extra grande, Ã¡reas principais |

## Componentes de UI

### BotÃµes

#### Button Primary
- **Tamanho:** Height 48px minimum (iOS/Android compliance)
- **Background:** #4A90E2
- **Texto:** #FFFFFF, Inter Medium 14px
- **Border Radius:** 8px
- **Padding:** 12px 24px
- **Estados:** Default, Hover (#6BB6FF), Pressed (#3A7BC8), Disabled (#C7C7CC)

#### Button Secondary
- **Tamanho:** Height 48px minimum
- **Background:** Transparent
- **Border:** 1px #4A90E2
- **Texto:** #4A90E2, Inter Medium 14px
- **Estados:** Default, Hover (Background: #F2F2F7), Pressed, Disabled

### Inputs e FormulÃ¡rios

#### Text Input
- **Tamanho:** Height 48px minimum, Width: Full container
- **Background:** #FFFFFF
- **Border:** 1px #C7C7CC
- **Font:** Inter Regular 16px
- **Border Radius:** 8px
- **Padding:** 12px 16px
- **Estados:** Default, Focus (Border: #4A90E2), Error (Border: #FF3B30), Disabled

### Containers

#### Card
- **Background:** #FFFFFF
- **Border Radius:** 12px
- **Shadow:** 0 2px 8px rgba(0,0,0,0.1)
- **Padding:** 16px
- **Estados:** Default, Hover (Shadow: 0 4px 12px rgba(0,0,0,0.15)), Pressed

#### List Item
- **Tamanho:** Height 56px minimum
- **Background:** #FFFFFF
- **Padding:** 12px 16px
- **Border Bottom:** 1px #F2F2F7
- **Estados:** Default, Hover, Selected (Background: #F2F2F7), Pressed

### NavegaÃ§Ã£o

#### Bottom Navigation
- **Tamanho:** Height 80px (iOS safe area), Width: Full screen
- **Background:** #FFFFFF
- **Shadow:** 0 -2px 8px rgba(0,0,0,0.1)
- **Padding:** 8px 0
- **Estados:** Default, Active (Icon: #4A90E2, Text: #4A90E2)

#### Header
- **Tamanho:** Height 64px + status bar, Width: Full screen
- **Background:** #FFFFFF
- **Shadow:** 0 2px 4px rgba(0,0,0,0.1)
- **Title:** Inter SemiBold 18px

### Outros Componentes

#### Chip
- **Tamanho:** Height 32px
- **Background:** #F2F2F7
- **Texto:** #3A3A3C, Inter Medium 12px
- **Border Radius:** 16px
- **Padding:** 6px 12px
- **Estados:** Default, Selected (Background: #4A90E2, Text: #FFFFFF), Disabled

#### Modal
- **Tamanho:** Width 90% container (max 400px mobile), Height: Variable
- **Background:** #FFFFFF
- **Border Radius:** 16px
- **Shadow:** 0 8px 24px rgba(0,0,0,0.3)
- **Overlay:** rgba(0,0,0,0.5)

## Ãcones

### EspecificaÃ§Ãµes Gerais
- **Tamanho padrÃ£o:** 24x24px
- **Tamanho pequeno:** 16x16px  
- **Tamanho grande:** 32x32px
- **Estilo:** Outline style para mÃ¡xima clareza
- **Touch target mÃ­nimo:** 48x48px para Ã­cones interativos

### Categorias de Ãcones

#### Pet Icons
- **Ãcones:** paw, dog, cat, bird, fish, rabbit
- **Estilo:** Outline e Filled versions
- **Uso:** IdentificaÃ§Ã£o de tipos de pets, categorizaÃ§Ã£o

#### Medical Icons
- **Ãcones:** syringe, pill, stethoscope, calendar, heart, thermometer
- **Estilo:** Outline style para clareza
- **Uso:** Vacinas, medicamentos, consultas, saÃºde

#### Navigation Icons
- **Ãcones:** home, calendar, profile, settings, search, add, back, close
- **Uso:** NavegaÃ§Ã£o principal e secundÃ¡ria

#### Action Icons
- **Ãcones:** edit, delete, share, save, download, upload, camera, location
- **Uso:** AÃ§Ãµes do usuÃ¡rio, CRUD operations

## Acessibilidade

### Diretrizes WCAG 2.2 AA

#### Contraste
- **Texto normal:** MÃ­nimo 4.5:1
- **Texto grande:** MÃ­nimo 3:1 (â‰¥18px ou â‰¥14px bold)
- **Elementos grÃ¡ficos:** MÃ­nimo 3:1

#### Touch Targets
- **Tamanho mÃ­nimo:** 48x48px
- **EspaÃ§amento:** 8px mÃ­nimo entre targets
- **Ãrea de toque clara e consistente**

#### NavegaÃ§Ã£o
- **Ordem lÃ³gica de foco**
- **Indicadores visuais de foco**
- **Suporte Ã  navegaÃ§Ã£o por teclado**
- **Screen reader compatibility**

#### Responsividade
- **Zoom atÃ© 200% sem perda de funcionalidade**
- **OrientaÃ§Ã£o flexÃ­vel (portrait/landscape)**
- **Texto responsivo e escalÃ¡vel**

## Dark Mode

### ImplementaÃ§Ã£o
O design system inclui suporte completo ao dark mode com:

- **Paleta de cores adaptada** para ambientes com pouca luz
- **Contraste otimizado** para legibilidade em telas escuras
- **TransiÃ§Ãµes suaves** entre temas
- **PreferÃªncias do sistema** respeitadas automaticamente

### Cores Dark Mode
- **Background Principal:** #1C1C1E
- **Background Cards:** #2C2C2E
- **Texto Principal:** #FFFFFF
- **Texto SecundÃ¡rio:** #EBEBF5
- **Borders:** #38383A
- **Primary Blue:** #0A84FF
- **Primary Green:** #30D158

## ImplementaÃ§Ã£o

### CSS Custom Properties
```css
:root {
  --color-primary: #4A90E2;
  --color-primary-green: #7ED321;
  --spacing-md: 16px;
  --font-family-primary: 'Inter', sans-serif;
  --border-radius-default: 8px;
}
```

### Responsividade
```css
@media (max-width: 480px) {
  .grid { grid-template-columns: repeat(4, 1fr); }
}

@media (min-width: 481px) and (max-width: 768px) {
  .grid { grid-template-columns: repeat(4, 1fr); }
}

@media (min-width: 769px) {
  .grid { grid-template-columns: repeat(8, 1fr); }
}
```

## Versionamento

### VersÃ£o 1.0 (Junho 2025)
- LanÃ§amento inicial do design system
- Componentes fundamentais
- Paleta de cores completa
- Sistema tipogrÃ¡fico
- Suporte a dark mode
- Diretrizes de acessibilidade

### Roadmap Futuro
- Componentes avanÃ§ados (data pickers, charts)
- AnimaÃ§Ãµes e micro-interaÃ§Ãµes
- Temas personalizÃ¡veis
- ExpansÃ£o da biblioteca de Ã­cones
- Componentes especÃ­ficos para veterinÃ¡rios

## Recursos e Ferramentas

### Figma
- Biblioteca de componentes disponÃ­vel
- Assets organizados por categoria
- Auto-layout configurado
- Variantes para estados diferentes

### Desenvolvimento
- CSS/SCSS tokens disponÃ­veis
- DocumentaÃ§Ã£o tÃ©cnica completa
- Exemplos de implementaÃ§Ã£o
- Testes de acessibilidade automatizados

---

**Contato:**  
Para dÃºvidas ou sugestÃµes sobre o design system, entre em contato com a equipe de Design.

**Ãšltima atualizaÃ§Ã£o:** Junho 2025
