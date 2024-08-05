# Semantic_Parsing

In this project, we implemented a LSTM based sequence-to-sequence model for semantic parsing.

- Firstm we implemented an encoder, an LSTM based decoder and then used it to train a basic sequence-to-sequence model.
- Next, we extended the decoder with attention and implement beam search decoding (a greedy decoder is provided as reference).
- Lastly the model is improved using extensions such as a copy mechanism or data augmentation.
We will use the Geoquery dataset (Zelle & Mooney, 2006) for this project which consists of questions about a small knowledge base of geographical entities, paired with meaning representations in the form of Prolog formulas.
