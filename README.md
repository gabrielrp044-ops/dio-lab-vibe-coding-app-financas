# 💸 # Fina — Assistente Financeiro Conversacional

Projeto desenvolvido para o desafio **App de Organização de Finanças Pessoais com Vibe Coding**, com uso do Lovable para a geração do conceito do MVP e do Microsoft Copilot para análise e aprimoramento do prompt.

---

## Sumário

1. [Visão geral](#visão-geral)
2. [Conceito do produto](#conceito-do-produto)
3. [Identidade visual](#identidade-visual)
4. [Prompt final (PRD)](#prompt-final-prd)
5. [Interações com a IA](#interações-com-a-ia)
6. [Validação inicial](#validação-inicial)
7. [Reflexão sobre o aprendizado](#reflexão-sobre-o-aprendizado)
8. [Ferramentas utilizadas](#ferramentas-utilizadas)

---

## Visão geral

Grande parte das pessoas abandona o controle financeiro porque os aplicativos disponíveis exigem entrada manual de dados, configuração de categorias e elaboração de orçamentos, processos percebidos como trabalhosos.

O **Fina** propõe uma alternativa: o controle financeiro realizado por meio de uma conversa. O usuário registra suas movimentações em linguagem natural, por exemplo:

- "Gastei 32 reais no almoço."
- "Recebi meu salário de 2.500 reais."
- "Quero juntar 1.000 reais até dezembro."

Um agente financeiro baseado em inteligência artificial interpreta a mensagem, registra a transação, classifica-a automaticamente e fornece recomendações personalizadas de economia.

---

## Conceito do produto

| Item | Descrição |
|---|---|
| **Problema** | Aplicativos financeiros exigem muita entrada manual e oferecem pouca personalização. |
| **Solução** | Registro de receitas e despesas por meio de chat em linguagem natural. |
| **Público-alvo** | Pessoas iniciantes em organização financeira, especialmente jovens e estudantes. |
| **Diferencial** | Agente de IA que classifica transações, acompanha metas e sugere economias sem exigir configuração prévia. |
| **Posicionamento** | Experiência visual sofisticada, inspirada em instituições financeiras de alto padrão. |

### Funcionalidades do MVP

1. **Chat financeiro:** registro de receitas e despesas em linguagem natural.
2. **Classificação automática:** categorização das transações em alimentação, transporte, lazer, moradia, saúde, educação e outros.
3. **Metas financeiras:** criação e acompanhamento de objetivos com indicador de progresso.
4. **Agente financeiro:** recomendações de economia baseadas no comportamento de consumo do usuário.
5. **Relatórios:** resumo mensal com gráfico de despesas por categoria.

### Estrutura de telas

| Tela | Finalidade |
|---|---|
| Onboarding | Apresentação do produto e definição da renda mensal. |
| Chat | Tela principal, onde ocorrem os registros e a interação com o agente. |
| Painel | Saldo do mês, despesas por categoria e últimas transações. |
| Metas | Lista de objetivos financeiros e respectivo progresso. |
| Relatório mensal | Consolidação do mês com gráficos e análises do agente. |

---

## Identidade visual

A paleta de cores foi definida com base em princípios de psicologia das cores, com o objetivo de transmitir confiança, sofisticação e tranquilidade, características associadas a instituições financeiras de alto padrão.

| Cor | Código | Função | Percepção associada |
|---|---|---|---|
| Azul-marinho | `#0B1220` | Fundo principal | Confiança, segurança e foco |
| Azul-grafite | `#141C2E` | Cards e superfícies | Profundidade e elegância |
| Dourado champanhe | `#D4AF6A` | Destaques e ações principais | Prestígio, conquista e valor |
| Verde-esmeralda | `#2EB88A` | Receitas, metas e valores positivos | Prosperidade, equilíbrio e crescimento |
| Coral suave | `#E5735F` | Alertas de gastos | Atenção sem gerar ansiedade |
| Marfim | `#F5F1E8` | Títulos | Leitura confortável e sofisticada |
| Cinza-claro | `#A9B1C1` | Textos secundários | Hierarquia visual e legibilidade |

**Tipografia:** Playfair Display nos títulos e Inter nos textos.

**Acessibilidade:** contraste entre texto e fundo em conformidade com o padrão WCAG AA.

**Interatividade:** botões, cards e itens de menu respondem à passagem do cursor com elevação, brilho dourado sutil e transições suaves entre 200 e 300 ms. As telas contam com animações discretas de entrada, gráficos animados e indicador de digitação no chat.

---

## Prompt final (PRD)

O prompt foi elaborado a partir do modelo proposto no desafio e utilizado no Lovable. Em seguida, foi submetido ao Microsoft Copilot para análise e sugestões de melhoria, registradas na seção [Interações com a IA](#interações-com-a-ia).

```
# Contexto
Quero criar um aplicativo web de Organização de Finanças Pessoais chamado "Fina", que funcione por meio de conversas com o usuário.
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes, jovens e estudantes.

# Funcionalidades-Chave
1. Registrar gastos e receitas via chat em linguagem natural, por exemplo: gastei 30 reais no almoço.
2. Classificar automaticamente as transações em categorias: alimentação, transporte, lazer, moradia, saúde, educação e outros.
3. Definir e acompanhar metas financeiras com barra de progresso.
4. Receber dicas de economia do Agente Financeiro, baseadas nos gastos do usuário.
5. Visualizar relatórios simples e personalizados, com gráfico de gastos por categoria.

# Telas
- Onboarding: boas-vindas e definição da renda mensal.
- Chat: tela principal, com mensagens do usuário e respostas do Agente Financeiro.
- Painel: saldo do mês, gastos por categoria e últimas transações.
- Metas: lista de objetivos com progresso.
- Relatório mensal: resumo com gráficos e insights.

# Identidade Visual (luxo e psicologia das cores)
O site deve transmitir sofisticação, exclusividade, segurança e calma, com estética de banco privado ou marca de luxo.
- Fundo principal: azul-marinho quase preto #0B1220, transmite confiança e foco.
- Cards e superfícies: azul-grafite #141C2E, com bordas finas e sutis.
- Destaque: dourado champanhe #D4AF6A, para botões principais, ícones e detalhes, usado com moderação.
- Crescimento: verde-esmeralda #2EB88A, para receitas, metas e valores positivos.
- Alerta: coral suave #E5735F, para gastos acima do esperado.
- Texto: marfim #F5F1E8 nos títulos e cinza-claro #A9B1C1 nos textos secundários.
Garantir contraste acessível padrão WCAG AA em todas as telas.
Tipografia: Playfair Display nos títulos e Inter nos textos.
Layout arejado, cantos levemente arredondados e sombras suaves.

# Interatividade
- Botões, cards, itens de menu e opções reagem ao passar o mouse: leve elevação, brilho dourado sutil na borda, mudança suave de cor e cursor de clique.
- Transições suaves de 200 a 300 ms em todas as interações.
- Animações discretas de entrada nas telas, com fade e deslize leve.
- Barras de progresso e gráficos animados ao aparecer.
- Mensagens do chat surgindo com animação suave e indicador de digitando do Agente Financeiro.
- Site responsivo para computador e celular.

# Tom do Agente Financeiro
Acolhedor, elegante, motivador e sem julgamentos, como um consultor financeiro pessoal.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial, e construir as telas seguindo a identidade visual descrita.
Usar tom educativo e linguagem acessível, em português.
```

---

## Interações com a IA

### Lovable: geração do MVP

![Plano do MVP gerado pelo Lovable]  <img width="1135" height="563" alt="fina copilot" src="https://github.com/user-attachments/assets/8508885f-a38c-4094-8f7f-9786935279cd" />


![Fluxo de telas](./images/lovable-telas.png)
![Tela de chat](./images/lovable-chat.png)
![Painel e metas](./images/lovable-painel.png)

**Projeto publicado no Lovable:** [acessar projeto](COLE_AQUI_O_LINK)

### Microsoft Copilot: análise e aprimoramento do prompt

![Solicitação de revisão no Microsoft Copilot](./images/copilot-prompt.png)
![Versão revisada pelo Microsoft Copilot](./images/copilot-revisao.png)

O Copilot reorganizou o prompt em seções mais objetivas, como objetivo, problema e solução proposta, reduzindo ambiguidades e tornando a especificação mais clara para interpretação por ferramentas de IA. Essa versão aprimorada servirá de base para as próximas iterações do projeto.

### Estratégia de interações

Considerando o limite de cinco interações diárias do plano gratuito do Lovable, cada solicitação foi planejada previamente:

| Etapa | Solicitação | Objetivo |
|---|---|---|
| 1 | Envio do PRD completo | Gerar o plano inicial do MVP. |
| 2 | Complemento do PRD | Reenviar as funcionalidades e a identidade visual, após o primeiro envio ter sido recebido de forma incompleta. |
| 3 | Construção da tela de chat | Validar a funcionalidade principal com exemplos de uso. |
| 4 | Construção do painel e da tela de metas | Demonstrar o acompanhamento financeiro. |
| 5 | Plano de validação com usuários | Definir os próximos passos do produto. |

---

## Validação inicial

Antes de um desenvolvimento completo, propõe-se validar o conceito com as seguintes ações:

- Apresentar o protótipo a dez pessoas do público-alvo e avaliar se compreendem o funcionamento sem explicação prévia.
- Coletar a percepção sobre frequência de uso e funcionalidades consideradas ausentes.
- Medir se os participantes conseguem registrar três transações pelo chat em menos de um minuto.

---

## Reflexão sobre o aprendizado

O principal aprendizado deste projeto foi compreender que a qualidade das respostas geradas pela IA está diretamente relacionada à clareza da solicitação. A estruturação da ideia em formato de PRD, contemplando problema, público, funcionalidades e identidade visual, resultou em entregas mais precisas e alinhadas à proposta.

Durante o processo, o primeiro envio do prompt ao Lovable foi recebido de forma incompleta, o que levou a ferramenta a solicitar as funcionalidades restantes. Essa situação evidenciou a importância de verificar o que a IA efetivamente interpretou e de reapresentar as informações de forma organizada, em vez de aceitar um resultado parcial.

A análise posterior com o Microsoft Copilot demonstrou que um prompt pode ser continuamente aprimorado. A reorganização sugerida pela ferramenta tornou a especificação mais objetiva e reforçou a prática de revisar e iterar sobre as próprias instruções.

O projeto também reforçou a importância do planejamento diante de recursos limitados, como o número de interações disponíveis, e a aplicação do conceito de MVP, priorizando as funcionalidades essenciais. Além disso, a especificação detalhada da identidade visual demonstrou como decisões de design influenciam a percepção de qualidade e credibilidade de um produto.

Por fim, ficou claro que o Vibe Coding acelera a execução, mas não substitui o raciocínio humano: a definição do problema, as decisões de produto e a validação permanecem como responsabilidade de quem desenvolve a solução.

---

## Ferramentas utilizadas

| Ferramenta | Finalidade |
|---|---|
| Lovable | Geração do plano do MVP e das telas |
| Microsoft Copilot | Análise e aprimoramento do prompt |
| GitHub | Documentação e versionamento do projeto |   
