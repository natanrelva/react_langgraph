# Aplication Sington Patter in Agent LLM device localhost.

```
src/
├── langgraph-agent/
│   ├── orchestrations/
│   │   ├── IndexedDBCheckpointer.ts  // Implementação do checkpointer personalizado
│   │   └── mainWorkflow.ts          // Definição do StateGraph e compilação
│   ├── agents/
│   │   └── conversationalAgent.ts   // Lógica do agente, prompts
│   ├── models/
│   │   └── geminiModelLLM.ts        // Instanciação do modelo LLM
│   └── tools/
│       └── index.ts                 // (Inicialmente vazio ou com ferramentas simples)
```

**With**:
- reactJS + langchainjs. Arquitetura de solução evolucional do agente local percistido em seu proprio dispositivo. 

### **[ ANALISAR !! ]** Validação inplicitas
* Como a custodia das informações comportamentais dos cliente ficariam ao seu encargo. Ao passo que a evolução do sistema digital de sequa ao padrão comportamental do sujeito, da em quê?.

* Arquitetura tradicionais, como seria essa questão do roteamento em um sistema que precisa operar em evolução continua paralela ao usuário client. Anexo 1 Foto: ![Logo da empresa](https://langchain-ai.github.io/langgraphjs/tutorials/multi_agent/img/simple_multi_agent_diagram.png)