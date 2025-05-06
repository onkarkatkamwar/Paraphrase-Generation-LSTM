# Paraphrase-Generation-LSTM

🚀 Project Spotlight: Paraphrase Generation using Deep Learning

Thrilled to share our recent project on Paraphrase Generation — rephrasing sentences while preserving their original meaning, with wide applications in NLP, chatbots, writing tools, and content diversification.

🔍 Goal:
To compare neural architectures (with & without attention) and analyze the impact of attention mechanisms on paraphrasing performance.

🛠 Models Explored:

LSTM Encoder-Decoder (No Attention) – Struggles with long sequences
Bahdanau Attention – Better context handling for longer inputs
Transformer (Self-Attention) – Best performance, high compute cost

📘 Approach:

Used the ChatGPT Paraphrases dataset from HuggingFace
Built models with TensorFlow/Keras
Evaluated using BLEU, ROUGE-L, METEOR metrics

📊 Results:

No Attention: BLEU 0.0214 | ROUGE-L 0.1493
With Attention: BLEU 0.0356 | ROUGE-L 0.1989
Transformer: BLEU 0.0377 | ROUGE-L 0.2017

💡 Key Takeaways:

Attention boosts performance significantly
Transformers outperform but are compute-heavy
Bahdanau offers a great trade-off between complexity and results

👥 Team:
Onkar Katkamwar, Vidhisha Deshmukh, Prajwal Ganar
📌 Poster attached for a visual summary!
📚 Ref: Bowman et al., arXiv:1511.06349

#DeepLearning #NLP #ParaphraseGeneration #AttentionMechanism #Transformer #AI #MLProjects #TensorFlow #AcademicResearch
