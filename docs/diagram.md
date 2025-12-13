```mermaid
flowchart LR
    subgraph APP[APLIKACJA: Planer Studenta]
        S[Student 18-25Lat]
        A[Dodaj zadanie]
        B[Ustaw priorytet]
        C[Ustaw przypomnienie]
        D[Kalendarz tygodniowy]
        E[Edytuj / Usuń zadanie]
        F[Filtruj / Sortuj zadania]
        G[Śledź statystyki postępów]
    end

    S --> A
    S --> B
    S --> C
    S --> D
    S --> E
    S --> F
    S --> G
