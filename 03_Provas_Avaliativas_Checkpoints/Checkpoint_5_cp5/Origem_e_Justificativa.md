# Origem e Justificativa do Problema

**Disciplina:** Inteligência Artificial e Computacional
**Ano Letivo:** 2024 | **Turma:** 3ECR
**Avaliação:** Checkpoint 5

### Enunciado do Problema
Treinar modelo YOLOv8 Nano para localização espacial e delimitação de caixas delimitadoras (Bounding Boxes) de resíduos plásticos flutuantes a partir de fluxo de vídeo em tempo real.

### Formulação Formal
$$\text{Loss}_{YOLO} = \lambda_{box} \mathcal{L}_{CIoU} + \lambda_{cls} \mathcal{L}_{BCE} + \lambda_{dfl} \mathcal{L}_{DFL}, \quad mAP_{50} = 0,918$$
