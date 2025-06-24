# 🧠 Language Studio - Análise de Intenção

## 🎯 Objetivo
Detectar intenção e sentimento do trecho com **Conversational Language Understanding**.

## 🔤 Frase usada
```
Imagine all the people living life in peace.
```

## 🧠 Intenções cadastradas no modelo:
- `Falar sobre paz`
- `Mensagem filosófica`
- `Outro`

## 🔍 Resultado do modelo:
```json
{
  "topIntent": "Falar sobre paz",
  "confidenceScore": 0.93
}
```

## 📄 Arquivos de apoio
- `intents_config.json`
- `resultado_classificacao.json`

## 📌 Observações
- Modelo entendeu bem a intenção "paz" com alta confiança.
- Poderia ser integrado com bots, assistentes ou análise de sentimento.