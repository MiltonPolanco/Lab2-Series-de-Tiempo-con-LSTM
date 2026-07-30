# Laboratorio 2 - Deep Learning

En este laboratorio se construyen modelos LSTM para pronosticar dos de las
series temporales trabajadas en el Laboratorio 1:

- Total mensual de viajeros.
- Viajeros provenientes de América del Norte.

Se conserva la división cronológica anterior de 70% para entrenamiento y 30%
para prueba. Para cada serie se evalúan redes LSTM simples y apiladas con
distintas configuraciones. El mejor modelo se selecciona según su RMSE de
validación.

## Estructura

```text
03_deep_learning/
├── data/raw/                    # base original
├── notebooks/laboratorio_2.ipynb
├── requirements.txt
└── README.md
```

El notebook contiene la preparación de datos, el tuneo de parámetros, las
predicciones, las métricas y las gráficas.