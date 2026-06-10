# Diagrama del projecte

Aquest diagrama mostra el flux de treball que seguirà l'alumnat per crear una animació amb stop motion.

```mermaid
graph TD
    A[Idea inicial] --> B[Guió o storyline]
    B --> C[Storyboard]
    C --> D[Escenografia i personatges]
    D --> E[Rodatge fotografia a fotografia]
    E --> F[Muntatge del vídeo]
    F --> G[Afegir so, música i títols]
    G --> H[Presentació a classe]
```

!!! example "Lectura del diagrama"
    El procés comença amb una idea senzilla i acaba amb la presentació del vídeo final davant dels companys.

## Diagrama de responsabilitats del grup

```mermaid
flowchart LR
    G[Grup de 3 persones] --> P1[Guió i storyboard]
    G --> P2[Escenografia i personatges]
    G --> P3[Fotos i muntatge]
    P1 --> VF[Vídeo final]
    P2 --> VF
    P3 --> VF
```
