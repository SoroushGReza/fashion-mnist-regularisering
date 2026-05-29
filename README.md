# Fashion MNIST – Regularisering i CNN

Deep learning-projekt där en CNN-modell tränas för att klassificera bilder från Fashion MNIST.

## Fokusområde

Projektets fokusområde är regularisering.

Följande modeller jämförs:

* Grundmodell utan regularisering
* Modell med Dropout
* Modell med Dropout och Early Stopping

## Projektstruktur

```text
notebook/
    fashion_mnist_regularisering.ipynb

report/
    rapport.md

images/
    diagrams and training plots

models/
    saved model files
```

## Resultat

| Modell                   | Test Accuracy |
| ------------------------ | ------------- |
| Grundmodell              | 90.82 %       |
| Dropout                  | 89.53 %       |
| Dropout + Early Stopping | 90.14 %       |

## Inlämning

Huvudrapport finns i:

```text
report/rapport.md
```

Notebook med kod och analys finns i:

```text
notebook/fashion_mnist_regularisering.ipynb
```
