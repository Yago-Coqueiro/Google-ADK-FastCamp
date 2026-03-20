# Google ADK — FastCamp Agentes Inteligentes

Repositório desenvolvido como parte do **FastCamp de Agentes Inteligentes**, organizado em duas seções principais.

---

## google_adk_aula

Contém os códigos de acompanhamento dos tutoriais oficiais do Google ADK:

- **Quickstart — Build a Multi-Tool Agent:** implementação do tutorial introdutório, com um agente de clima e horário executado via interface web do ADK.
- **Progressive Weather Bot with ADK:** notebook baseado no tutorial avançado, que constrói progressivamente um sistema multiagente cobrindo ferramentas, delegação, session state e guardrails com callbacks.

---

## google_adk_pratica

Contém o projeto original de prática: um **Health Assistant Agent Team** aplicado à área da saúde. O sistema é composto por um agente raiz coordenador e dois sub-agentes especializados — um para análise de sintomas e outro para informações sobre medicamentos — com guardrails de segurança para situações de emergência médica e medicamentos controlados.

> ⚠️ O projeto de prática é estritamente educacional e não substitui consulta médica profissional.

---

## Como executar

Insira sua chave de API do Gemini na célula de configuração de cada notebook e execute as células em ordem. Obtenha sua chave em [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey).

```bash
pip install google-adk
```

---

**Autor:** Yago Lima Coqueiro
