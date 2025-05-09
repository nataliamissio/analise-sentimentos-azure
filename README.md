# Análise de Sentimentos com Azure AI Language Studio

## 🧠 Sobre o Projeto
Este projeto foi criado como parte de um desafio de portfólio, utilizando o **Azure AI Language Studio** para realizar análise de sentimentos de diferentes sentenças de texto.

## 📝 Input
Criei um arquivo `inputs/sentencas.txt` com algumas frases de exemplo:

## 📝 Input
Criei um arquivo `inputs/sentencas.txt` com frases variadas para simular diferentes tipos de sentimentos. Aqui estão algumas delas:

- A apresentação foi excelente, todos adoraram!
- Estou muito satisfeita com o resultado final.
- O sistema apresentou vários erros inesperados.
- Infelizmente, tivemos muitos problemas durante o processo.
- Recebi a encomenda hoje de manhã.
- A reunião começou às 14h como previsto.

Essas frases foram analisadas pelo Azure AI Language Studio para identificar os sentimentos associados: positivo, negativo ou neutro.

## ⚙️ Etapas do Processo

1. Acesse o [Azure AI Language Studio](https://language.azure.com/)
2. Selecione a opção **Análise de Sentimentos**
3. Copiei e colei as frases do arquivo de entrada
4. A IA analisou as sentenças e retornou os sentimentos (positivo, negativo, neutro)

## 📸 Prints do Processo

### 🔍 Input no Azure Language Studio
![Input](prints\input.png)

### 📊 Resultado da análise
![Resultado](prints\resultado.png)

## 💡 Insights

- Frases com palavras negativas como "frustrado" ou "infelizmente" foram classificadas como **negativas**
- Frases com palavras positivas como "incrível" ou "ótima" foram corretamente identificadas como **positivas**
- Frases mais ambíguas podem cair na categoria **neutra**

## 🚀 Possibilidades

- Usar essa análise para entender feedbacks de clientes
- Aplicar em reviews de produtos ou serviços
- Integrar em sistemas de atendimento ou redes sociais

---

### 📎 Conclusão

Esse experimento demonstrou como é simples e poderoso utilizar ferramentas de IA do Azure para compreender emoções e sentimentos a partir de linguagem natural.

