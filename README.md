# TechnicalWriter
```mermaid
flowchart TD
    Start([START]) --> A[Cek Kondisi Rem]
    A --> B{Rem Normal?}
    B -->|Tidak| C[Perbaiki Rem]
    C --> B
    B -->|Ya| D{Ban Cukup Keras?}
    D -->|Tidak| E[Pompa Ban]
    E --> D
    D -->|Ya| F{Rantai Bagus?}
    F -->|Tidak| G[Kencangkan Rantai]
    G --> F
    F -->|Ya| H[Berdiri di Sisi Kiri]
    H --> I[Genggam Stang]
    I --> J[Atur Pedal Kiri Atas]
    J --> K[Pijak Pedal Kiri]
    K --> L[Tekan Pedal & Angkat Tubuh]
    L --> M[Duduk di Sadel]
    M --> N[Tempatkan Kaki Kanan]
    N --> O[SET kondisi = sedang_berkendara]
    O --> P[Injak Pedal Bergantian]
    P --> Q{Kondisi == sedang_berkendara?}
    Q -->|Ya| R{Perlu Belok?}
    R -->|Ya| S[Putar Stang & Miringkan]
    S --> T{Ingin Mempercepat?}
    R -->|Tidak| T
    T -->|Ya| U[Kayuh Lebih Cepat]
    U --> V{Perlu Melambat?}
    T -->|Tidak| V
    V -->|Ya| W[Kurangi Tempo & Rem]
    W --> X{Hendak Berhenti?}
    V -->|Tidak| X
    X -->|Tidak| P
    X -->|Ya| Y[SET kondisi = akan_berhenti]
    Q -->|Tidak| Y
    Y --> Z[Hentikan Kayuhan]
    Z --> AA[Aplikasikan Rem]
    AA --> AB[Turunkan Satu Kaki]
    AB --> AC[Turunkan Kaki Lain]
    AC --> AD[Turun dari Sadel]
    AD --> AE[Parkir Sepeda]
    AE --> End([END])
