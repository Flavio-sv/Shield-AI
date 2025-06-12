# Shield AI - Detector de Discurso de Ódio e Bullying em Português

Este projeto utiliza técnicas de Processamento de Linguagem Natural (PLN) e aprendizado de máquina para detectar automaticamente discurso de ódio, bullying e toxicidade em comentários.

## 🚀 Tecnologias Utilizadas

- Python 3.x
- TensorFlow / Keras
- NLTK
- Pandas, NumPy, Matplotlib
- Gradio (interface web interativa)

## 📋 Descrição

O sistema foi desenvolvido para identificar automaticamente diferentes tipos de toxicidade em textos, incluindo:
- Tóxico
- Extremamente Tóxico
- Obsceno
- Ameaça
- Insulto
- Ódio Identitário

O modelo utiliza uma rede neural LSTM bidirecional treinada sobre um dataset público de comentários rotulados.

## 🛠️ Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Flavio-sv/Shield-AI.git
   ```

3. **Execute o notebook Jupyter:**
   ```bash
   Shield_AI.ipynb
   ```

> ⚠️ **Atenção:** Use o Python 3.12.0

## 📊 Resultados

O modelo foi executado durante 10 épocas de treinamento.

- **Precisão:** 0.86
- **Recall:** 0.87
- **Acurácia:** 0.33
- **Loss final:** 0.0780
- **Val_loss final:** 0.0705

O modelo apresenta bom desempenho na detecção de toxicidade, especialmente em classes mais frequentes.

## ⚠️ Limitações

- Pode apresentar falsos positivos em textos ambíguos ou sarcásticos.
- Depende da qualidade e representatividade do dataset.
- Dificuldade em interpretar contexto amplo ou gírias regionais.

## 📄 Licença

Este projeto é de uso acadêmico.
