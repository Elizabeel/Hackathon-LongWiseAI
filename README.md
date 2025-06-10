# 🥉 Lugar no Hackathon de IA e Multi-Cloud do Cubo Itaú !

#👥 O desafio proposto envolvia um cenário em cima de dores reais trazidas pelo próprio Itaú, e deveriamos solucionar algum desses problemas construindo uma arquitetura sólida. 

🔎 Focamos em como identificar e reduzir o desperdício causado por logs desnecessários, antes mesmo deles gerarem custos. 

📈 Em ambientes com milhares de contas, como no Itaú, o volume de logs gerados cresce de forma exponencial. E muitos desses dados, apesar de consumirem recursos (armazenamento, processamento, observabilidade), não geram valor analítico real.

#💡 Dessa forma criamos o LongWise um agente inteligente que atua no fluxo de desenvolvimento para:

✅ Analisar código e logs com IA generativa (Amazon Bedrock)
✅ Identificar padrões de ineficiência antes do deploy
✅ Sugerir melhorias e enviar alertas direto no pull request ou Slack
✅ Educar desenvolvedores em práticas de FinOps, promovendo eficiência contínua

📊 Com o MVP, conseguimos:

Reduzir até 35% no volume de logs inúteis

Estimar economias reais com base em dados CloudWatch e Cost Explorer

Mostrar que é possível unir observabilidade, cloud e IA de forma automatizada e inteligente

## 💡 Nossa Solução: LogWise AI

O **LogWise AI** é um agente inteligente e contínuo, criado com **Amazon Bedrock**, que atua **no fluxo natural de desenvolvimento**. Ele analisa código, padrões de logs e comportamento de uso **antes do deploy** e identifica possíveis pontos de desperdício, como:

- Loops custosos e repetitivos;
- Funções Lambda superdimensionadas;
- Timeouts mal configurados;
- Logs de debug esquecidos em produção;
- Chamadas desnecessárias a serviços como o S3.

---

## 🤖 Como Funciona

O agente:

1. Acompanha o pipeline de desenvolvimento;
2. Coleta código e logs diretamente da esteira;
3. Utiliza modelos generativos da **Amazon Bedrock** para análise;
4. Retorna sugestões e alertas de eficiência direto no **pull request** ou via **Slack**.

> 💬 Não estamos criando mais um dashboard. Estamos criando um **copiloto de eficiência**, que orienta os desenvolvedores em tempo real e promove uma cultura de responsabilidade técnica e financeira.

---

## 🧪 MVP

Nosso MVP foca em:

- Linguagem **Python** com deploy em **AWS Lambda**;
- **3 tipos principais de desperdício identificados**;
- Integração com **GitHub** e **CloudWatch**;
- Output de recomendações via **Slack** ou **comentários no PR**.

### 🎯 Métricas mensuradas no MVP:
- Redução de logs desnecessários;
- Otimizações aplicadas diretamente no código;
- Estimativas de **custo evitado** por aplicação.

---

## 🌱 Por que isso importa?

Em vez de reagir ao custo **depois que ele acontece**, o LogWise AI promove uma abordagem **preventiva** e **educativa**:

- Reduz gastos invisíveis com observabilidade;
- Aumenta a eficiência do código;
- Incentiva boas práticas de desenvolvimento;
- Escala de forma segura e automatizada.

---

## 📌 Próximos Passos

- Suporte para mais linguagens (Java, Node.js);
- Expansão para ambientes com containers (ECS, EKS);
- Dashboard com insights financeiros e técnicos;
- Mecanismo de aprendizado com feedback do usuário.

---

## 🧠 Conclusão

> “Se queremos uma TI mais moderna, ágil e sustentável, ela precisa ser guiada por decisões inteligentes em cada linha de código.”

O **LogWise AI** está pronto para transformar desperdício invisível em eficiência contínua — basta dar o sinal verde. 💚

---

## 🔗 Tecnologias

- Amazon Bedrock
- AWS Lambda
- CloudWatch
- GitHub
- Slack API
