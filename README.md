# 🎨→⬜ Conversor de Imagem: Colorida → Tons de Cinza → Binária

Implementação em **Python puro** (sem bibliotecas externas) que lê uma imagem colorida,
converte para níveis de cinza (0–255) e depois binariza (0 e 255, preto e branco).

O projeto usa imagem de objetos geométricos.

---

## 📌 Sobre o projeto

Este repositório demonstra, de forma didática, **o que acontece por baixo dos panos**
quando uma biblioteca como OpenCV ou Pillow converte uma imagem. Todo o pipeline é
escrito à mão, usando apenas recursos nativos da linguagem Python.

O fluxo é:

Imagem colorida (RGB) → Tons de cinza (0–255) → Binária (0 e 255) PPM (P3) luminância BT.601 limiar global
