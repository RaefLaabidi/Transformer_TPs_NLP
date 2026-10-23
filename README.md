# Transformer TPs NLP

Ce depot contient quatre notebooks progressifs pour reconstruire un mini-Transformer caractere par caractere :

1. [TP1_bigramme.ipynb](./TP1_bigramme.ipynb) : corpus, tokenisation et modele bigramme.
2. [TP2_auto_attention.ipynb](./TP2_auto_attention.ipynb) : moyenne causale, masque et auto-attention.
3. [TP3_layernorm_mlp.ipynb](./TP3_layernorm_mlp.ipynb) : LayerNorm, MLP et residuels.
4. [TP4_transformer_complet.ipynb](./TP4_transformer_complet.ipynb) : assemblage, entrainement, evaluation et generation.

Les notebooks utilisent PyTorch et telechargent `input.txt` depuis Tiny Shakespeare a la premiere execution. Le TP4 utilise `QUICK_RUN=True` pour une execution raisonnable sur CPU ; mettre cette option a `False` pour l'entrainement complet demande dans le sujet.
