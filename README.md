# Azure AI — Speech & Language Studio 🚀

Este repositório contém um guia prático para utilizar os estúdios **Azure Speech** e **Azure Language**, com workflows rápidos e sem necessidade de código.

---

## 🎙️ Azure Speech Studio

O **Speech Studio** é um conjunto de ferramentas UI para explorar e testar serviços de fala do Azure — incluindo transcrição, síntese, tradução e treinamento de modelos personalizados :contentReference[oaicite:1]{index=1}.

### Principais recursos
- **Transcrição (Speech-to-Text)**: teste em tempo real ou para lotes, sem código :contentReference[oaicite:2]{index=2}.  
- **Text-to-Speech**: voices neurais e criação de vozes personalizadas com SSML :contentReference[oaicite:3]{index=3}.  
- **Tradução de fala**: suporte a tradução entre vários idiomas :contentReference[oaicite:4]{index=4}.  
- **Reconhecimento por falante**, avaliação de pronúncia, palavras-chave customizadas e galeria de vozes customizadas :contentReference[oaicite:5]{index=5}.

### Como usar
1. Acesse [https://ai.azure.com](https://ai.azure.com)  
2. Crie um projeto **Speech** em Azure AI Foundry  
3. No playground do Speech, faça upload de um arquivo de áudio e teste transcrição em tempo real  
4. Explore TTS, tradução, reconhecimento e vozes customizadas

---

## 📄 Azure Language Studio

O **Language Studio** reúne ferramentas para análise avançada de texto via NLP (NLP, NER, sumarização etc.) :contentReference[oaicite:6]{index=6}.

### Funcionalidades principais
- **Named Entity Recognition (NER)**: identifica nomes, locais, organizações  
- **Extração de frases-chave**: identifica termos importantes  
- **Análise de sentimento e opinion mining**  
- **Summarização**: extrativa ou abstrativa, e segmentação de reuniões  
- **PII detection, Entity Linking, Text Analytics for health** :contentReference[oaicite:7]{index=7}  
- **Custom ML**: classificação, NER customizado, CLU (intent + entidade), Q&A, workflows de orquestração :contentReference[oaicite:8]{index=8}

### Como usar
1. Crie um projeto **Language** no Azure AI Foundry  
2. Acesse o playground de Language  
3. Teste:
   - extração de nomes e entidades;
   - extração de frases-chave;
   - análise de sentimento;
   - sumarização de textos ou transcrições;
   - intents com CLU ou QA.
4. Exporte modelos e integre via SDK, CLI ou REST

---

## 🛠️ Como integrar

- Use o **Speech SDK / CLI / REST** para implementar transcrição, síntese, tradução, reconhecimento :contentReference[oaicite:9]{index=9}  
- Use o **Language SDK / REST** para análise de texto, clasificación, QA, intents :contentReference[oaicite:10]{index=10}

---

## ✅ Recursos e links úteis

- [Speech Studio - Visão geral](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/speech-studio-overview)
- [Text-to-Speech com SSML](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/speech-synthesis-markup)
- [Azure Language Studio - Visão geral](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/language-studio)
- [Reconhecimento de Entidades Nomeadas (NER)](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/named-entity-recognition/overview)
- [Sumarização de texto](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/summarization/overview)
- [Análise de sentimento](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/sentiment-opinion-mining/overview)
- [Conversational Language Understanding (CLU)](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/conversational-language-understanding/overview)

---

## 💡 Dicas
- Use a versão gratuita do Azure para testes rápidos sem custo inicial  
- Sempre delete os recursos não utilizados para evitar cobranças  
- Explore vozes customizadas, análise de sentimento e Q&A para seus casos de uso

---

## 📚 Próximos passos

- Adicionar exemplos de código em Python, C#, JS  
- Incluir amostras de áudio/texto para testes interativos  
- Entrar com workflow de CI/CD para automação

---
