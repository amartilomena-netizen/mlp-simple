
# Informe del experimento MLP
## Arquitectura
Model: "sequential"
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Layer (type)                    ┃ Output Shape           ┃       Param # ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
│ dense (Dense)                   │ (None, 64)             │        50,240 │
├─────────────────────────────────┼────────────────────────┼───────────────┤
│ dense_1 (Dense)                 │ (None, 10)             │           650 │
└─────────────────────────────────┴────────────────────────┴───────────────┘
 Total params: 152,672 (596.38 KB)
 Trainable params: 50,890 (198.79 KB)
 Non-trainable params: 0 (0.00 B)
 Optimizer params: 101,782 (397.59 KB)

## Métricas finales
- Test loss: 0.3373892307281494
- Test accuracy: 0.9010000228881836
## Fecha
Thu Nov  6 14:22:22 2025
