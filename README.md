# Agente Calculadora no Azure Foundry

## Descrição do Projeto
Este projeto implementa um **agente simples de calculadora** utilizando o **Azure Foundry** e o modelo `gpt-4o-mini`.  
O objetivo é demonstrar como criar, configurar e testar um agente funcional com pelo menos uma ação, cumprindo os requisitos do desafio.

---

## Objetivo do Agente
- Realizar operações matemáticas básicas: **soma, subtração, multiplicação e divisão**.  
- Retornar mensagens claras em casos de erro (ex.: divisão por zero).  
- Servir como exemplo de agente funcional no Foundry.

---

## Configuração
- **Assinatura:** Pay-as-you-go  
- **Recurso:** Azure OpenAI  
- **Modelo implantado:** `gpt-4o-mini`  
- **Tipo de implantação:** Standard  
- **Ação adicionada:** Intérprete de código  

---

## Prints de Execução
### 1. Criação do recurso Azure OpenAI

<img width="960" height="410" alt="2025-11-23_21h02_10" src="https://github.com/user-attachments/assets/4c214f44-cbb3-42b1-8eea-143a92838c85" />


### 2. Projeto e agente no Foundry

<img width="959" height="413" alt="2025-11-23_21h02_38" src="https://github.com/user-attachments/assets/dfcd174f-347f-428b-a1b4-d577cdce78cb" />

### 3. Configuração do agente e ação adicionada (prompt do sistema)

<img width="960" height="413" alt="2025-11-23_21h03_32" src="https://github.com/user-attachments/assets/277c4d08-0c40-485d-b092-d61f50bd3d29" />

### 5. Testes no Playground
- Entrada: `2+3` → Saída: `5`
  
<img width="960" height="418" alt="2025-11-23_20h59_50" src="https://github.com/user-attachments/assets/9b19ab50-cfc9-4e0e-900c-d156c8ba2534" />

- Entrada: `10/2` → Saída: `5`
 
<img width="960" height="414" alt="2025-11-23_21h00_37" src="https://github.com/user-attachments/assets/a7c1388a-4362-4d34-9a8f-3da44ca535e2" />

- Entrada: `4*5` → Saída: `20`
  
<img width="960" height="417" alt="2025-11-23_21h04_19" src="https://github.com/user-attachments/assets/7b2ee2cc-5e48-4b13-a3fd-46d5a8dabbb8" />
  
- Entrada: `10/0` → Saída: `Erro: divisão por zero não permitida`  
  
<img width="960" height="412" alt="2025-11-23_21h04_53" src="https://github.com/user-attachments/assets/a6a060fa-a7a1-4049-aa51-98d5fd3af64e" />

---

## Referências
- [Azure Foundry](https://learn.microsoft.com/azure/ai-services/openai/foundry-overview)  
- [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/overview)  
- [Power Automate](https://learn.microsoft.com/power-automate/)  

---

## Conclusão
Este repositório demonstra um agente funcional criado no **Azure Foundry**, com uma ação de cálculo simples usando o **Intérprete de código**.  
O projeto atende às exigências:  
- Repositório público no GitHub  
- README completo com descrição, objetivo, prints e referências  
- Agente funcional com pelo menos uma ação  
