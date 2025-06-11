# MeuPetVida – Design System & UI Kit

**Design System para aplicativo de gestão de pets brasileiros**

- **Mobile First**
- **Acessível**
- **Pet Friendly**
- **Brasil**
- **Interface limpa, moderna e amigável**
- **Facilita o cuidado com cães e gatos**
- **Inspirado nas melhores práticas de UX**
- **Adaptado para o mercado brasileiro**

---

## Paleta de Cores

| Nome                | Código HEX   | RGB                | Uso/Aplicação                        |
|---------------------|--------------|--------------------|--------------------------------------|
| Primary Blue        | #4A90E2      | 74, 144, 226       | Cor principal da marca               |
| Primary Light       | #EBF4FF      | 235, 244, 255      | Fundos claros                        |
| Secondary Green     | #7ED321      | 126, 211, 33       | Sucesso e saúde                      |
| Secondary Light     | #F0FDF4      | 240, 253, 244      | Fundos claros                        |
| Accent Beige        | #F5F5DC      | 245, 245, 220      | Destaque quente                      |
| Background          | #F9FAFB      | 249, 250, 251      | Fundo principal                      |
| Card                | #FFFFFF      | 255, 255, 255      | Fundo dos cards                      |
| Muted               | #F3F4F6      | 243, 244, 246      | Fundos sutis                         |
| Success             | #22C55E      | 34, 197, 94        | Ações positivas                      |
| Warning             | #F59E0B      | 245, 158, 11       | Atenção necessária                   |
| Destructive         | #EF4444      | 239, 68, 68        | Estados de erro                      |

---

## Tipografia

**Fonte principal:** Inter

| Nome         | Exemplo de uso                              |
|--------------|---------------------------------------------|
| Display      | MeuPetVida                                  |
| Heading 1    | Cuidar do seu pet nunca foi tão fácil       |
| Heading 2    | Organize a vida do seu pet                  |
| Heading 3    | Próximas vacinas                            |
| Body Large   | Mantenha todos os dados de saúde...         |
| Body         | Cadastre as informações do seu pet...       |
| Body Small   | Última atualização: hoje às 14:30           |
| Caption      | PRÓXIMA CONSULTA                            |

**Pesos e tamanhos:**  
- **Light (300):** Texto secundário  
- **Regular (400):** Texto principal  
- **Medium (500):** Labels  
- **Semibold (600):** Títulos  
- **Bold (700):** Destaques  
- **Extra Bold (800):** Headers  

---

## Botões

- **Altura:** 48px
- **Border radius:** 8px
- **Touch area mínima:** 48x48px

| Tipo         | Exemplo              |
|--------------|---------------------|
| Primário     | Cadastrar Pet       |
| Secundário   | Agendar Consulta    |
| Outline      | Ver Histórico       |
| Desabilitado | Desabilitado        |

**Icon Buttons:**  
Adicionar Cão, Adicionar Gato, +

**Estados interativos:**  
- **Hover:** 90% opacidade  
- **Active:** 80% opacidade  
- **Focus:** Anel de foco com 2px de offset  
- **Disabled:** 50% opacidade, sem pointer events  
- **Transition:** 200ms ease-out  

---

## Campos de Entrada

- **Altura:** 48px
- **Border radius:** 8px
- **Padding horizontal:** 16px (4 x 4px grid)
- **Focus ring:** 2px com offset de 2px
- **Placeholder:** Cor muted-foreground
- **Transições suaves:** 200ms

| Estado         | Exemplo                          |
|----------------|----------------------------------|
| Normal         | Nome do Pet (Ex: Buddy)          |
| Erro           | Campo obrigatório                |
| Sucesso        | Valor válido                     |
| Desabilitado   | Campo desabilitado               |

---

## Cards

- **Border radius:** 12px
- **Padding:** 16px
- **Fundo:** Branco (#FFFFFF)
- **Sombra:** Sutil

**Tipos de Cards:**
- **Básico:** Informações básicas do pet
- **Próximos Eventos:** Consultas, vacinas e medicamentos agendados
- **Pet Profile:** Saudável, Buddy, Golden Retriever, 3 anos, Vacinado, Luna, Persa, 2 anos, Consulta em breve
- **Action Cards:** Agendar, Nova consulta, Vacinas, Histórico, Medicamentos, Lembretes

**Diretrizes:**
- **Shadow:** Sutil para elevação
- **Hover:** Aumento sutil da sombra
- **Contraste máximo:** Para acessibilidade
- **Espaçamento interno:** Grid de 8px

---

## Ícones

- **Tamanho padrão:** 24x24px (w-6 h-6)
- **Estilo:** Outline
- **Cores:** Tokens semânticos (primary, secondary, etc.)
- **Contextual:** Ícones menores (20px) em componentes pequenos
- **Acessibilidade:** Sempre com labels ou contexto claro

**Exemplos de ícones:**  
- **Dog:** Representação de cães  
- **Paw Print:** Pegadas de pets  
- **Cat:** Representação de gatos  
- **Syringe:** Vacinas e injeções  
- **Pill:** Medicamentos  
- **Calendar:** Agendamentos  

---

## Sistema de Layout

- **Grid:** 8pt (8px, 16px, 24px, 32px, 40px, 48px, 56px, 64px...)
- **Touch targets mínimos:** 48x48px para acessibilidade
- **Margens laterais:** 16px mínimo em dispositivos móveis
- **Responsivo:** Mobile-first com breakpoints em 768px e 1024px
- **Densidade:** Adequada para uso com uma mão
- **Hierarquia visual:** Uso de espaçamentos para organizar conteúdo

---

## Componentes

| Componente         | Descrição/Exemplo                                      |
|--------------------|-------------------------------------------------------|
| Tabs               | Perfil, Saúde, Agenda                                 |
| Chips              | Cão, Gato, Saudável, Vacinado, 2 anos, Golden Retriever|
| Lists              | Consulta veterinária (15 Jun), Vacina antirrábica (22 Jun), Medicamento (2x ao dia), Diário |
| Modal              | Abrir Modal                                           |
| Alerts             | Sucesso: Dados salvos com êxito, Atenção: Consulta agendada em 24 horas, Erro: Falha ao conectar com o servidor |
| Bottom Navigation  | Início, Agenda, Pets, Config                          |

---

## Diretrizes de Acessibilidade

- **Contraste de cores:**  
  - Mínimo 4.5:1 para texto normal  
  - Mínimo 3:1 para texto grande  
  - Cores não como única forma de comunicação  
  - Suporte para modo escuro  
- **Interação:**  
  - Touch targets mínimos de 48x48px  
  - Estados de foco visíveis  
  - Feedback tátil e visual  
  - Navegação por teclado  

---

> **MeuPetVida Design System -  Criado com amor para pets brasileiros**
