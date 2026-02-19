# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

PRD Refinado no Copilot Web:

```
Quero criar um aplicativo de Organização de Finanças Pessoais com foco em simplicidade e interação por meio de conversas. O app deve ter:

1. Tela de Login Segura:
   - Autenticação com e-mail/senha ou biometria.
   - Criptografia de dados sensíveis.
   - Recuperação de senha com verificação em duas etapas.
   - Microanimações no botão de login e feedback visual em caso de erro.

2. Tela de Conversa (Chat Financeiro):
   - Registro de gastos em linguagem natural.
   - Classificação automática das transações.
   - Recomendações de economia do “Agente Financeiro”.
   - Feedback sonoro leve e ícones animados nas respostas.

3. Tela de Metas:
   - Metas representadas como caixinhas estilo Nubank.
   - Cada meta deve ter nome, valor alvo, valor já depositado e barra de progresso.
   - Feedback visual motivador (confete digital ou brilho ao alcançar a meta).
   - Animação suave na barra de progresso ao atualizar valores.

4. Dashboard de Gastos:
   - Visualização por categorias em cards (mercado, farmácia, estudos, passeios etc.).
   - Cards para gastos fixos.
   - Card para “Valor Poupado” com base no salário, mostrando quanto foi economizado no mês.
   - Gráficos intuitivos (pizza ou barras) com animação de entrada.
   - Efeitos hover nos cards (leve aumento de tamanho e sombra).

5. Tela de Relatórios:
   - Resumo mensal com insights automáticos.
   - Sugestões personalizadas de economia.
   - Comparação entre meses para mostrar evolução.
   - Destaques coloridos para insights positivos.

6. Estética e Acessibilidade:
   - Design em azul claro com efeito de glassmorphism nos cards.
   - Interface acessível (contraste adequado, suporte a leitores de tela, botões grandes e intuitivos).

Extras úteis:
- Onboarding inicial para configurar categorias e metas básicas.
- Feedback visual e textual para engajar o usuário.
- Tom educativo e linguagem acessível em português.

Objetivo:
Gerar um protótipo funcional, visualmente agradável e envolvente, que transmita leveza e simplicidade, com foco em iniciantes em organização financeira. Incluir microinterações e animações sutis para reforçar a experiência dentro do conceito de Vibe Coding.
```
#
Resultado final no Lovable: https://app-financa-carolinarlima.lovable.app/
#
![Animação](https://github.com/user-attachments/assets/04f478ab-4d27-4fff-b3b2-18171ed04393)

# 📊 Finança Fácil

**Finança Fácil** é um aplicativo web desenvolvido para auxiliar no controle das finanças pessoais de forma simples e prática.  
Ele oferece uma interface amigável e recursos essenciais para quem deseja organizar melhor sua vida financeira.

## ✨ Funcionalidades

- **Cadastro e Login de Usuário**  
  Crie sua conta e acesse suas informações de forma segura.

- **Gestão de Entradas e Saídas**  
  Registre receitas e despesas para acompanhar seu fluxo financeiro.

- **Visualização de Saldo**  
  Veja rapidamente o saldo disponível com base nos lançamentos feitos.

- **Organização Simples**  
  Interface intuitiva que facilita o uso mesmo para quem não tem experiência com apps de finanças.

- **Acessibilidade Web**  
  Pode ser acessado diretamente pelo navegador, sem necessidade de instalação.

## 🎯 Objetivo

O objetivo do **Finança Fácil** é tornar a gestão financeira acessível e descomplicada, permitindo que qualquer pessoa tenha controle sobre seus gastos e ganhos de forma prática.

---

💡 Ideal para quem busca uma solução leve e direta para organizar suas finanças pessoais.

#

## 📝 Reflexão sobre o processo de desenvolvimento

### ✅ O que funcionou bem
- Gerar um prompt detalhado no Copilot facilitou bastante o processo de desenvolvimento.  
- A interface criada ficou bonita, intuitiva e fácil de usar.  
- O Lovable conseguiu implementar todas as funcionalidades solicitadas, incluindo a criação de um banco de dados.  
- O fluxo de cadastro e login com **email e senha** funcionou perfeitamente.  
- Os valores gastos foram exibidos diretamente nos **cards**, tornando a experiência prática e visualmente clara.  
- O resultado final superou as expectativas iniciais.

### ⚠️ O que não funcionou como o esperado
- Algumas funcionalidades exigiram ajustes e refinamentos nos prompts para que fossem implementadas corretamente.  
- Foi necessário detalhar melhor as instruções para evitar ambiguidades durante a geração do app.  

### 📚 O que aprendi
- Aprendi a criar **prompts mais precisos e refinados**, o que impacta diretamente na qualidade do resultado.  
- Entendi a importância de especificar os detalhes do que desejo, para que a IA consiga entregar exatamente o que foi imaginado.  
- Descobri que conversar com IAs é um processo iterativo: quanto mais claro e detalhado o prompt, melhor o resultado.  
- Ganhei experiência em como alinhar expectativas e aproveitar ao máximo as ferramentas de IA no desenvolvimento de aplicações.  

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
