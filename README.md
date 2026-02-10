# TechnicalWriter
flowchart TD
    Start([MULAI]) --> A[Periksa Kondisi Sepeda]
    A --> B{Rem Berfungsi?}
    B -->|Tidak| C[Perbaiki Rem]
    C --> B
    B -->|Ya| D{Ban Cukup Angin?}
    D -->|Tidak| E[Pompa Ban]
    E --> D
    D -->|Ya| F[Posisi di Samping Kiri Sepeda]
    F --> G[Pegang Kedua Setang]
    G --> H[Injak Pedal Kiri ke Posisi Atas]
    H --> I[Dorong Pedal Kiri ke Bawah]
    I --> J[Naik ke Sadel]
    J --> K[Letakkan Kaki Kanan di Pedal]
    K --> L[Kayuh Pedal Bergantian]
    L --> M{Masih Berkendara?}
    M -->|Ya| N{Ingin Berbelok?}
    N -->|Ya| O[Arahkan Setang<br/>Condongkan Badan]
    O --> P[Terus Kayuh]
    N -->|Tidak| P
    P --> Q{Ingin Berhenti?}
    Q -->|Tidak| L
    Q -->|Ya| R[Hentikan Kayuhan]
    M -->|Tidak| R
    R --> S[Tekan Rem Perlahan]
    S --> T[Turunkan Kaki ke Tanah]
    T --> U[Turun dari Sadel]
    U --> V[Parkirkan Sepeda]
    V --> End([SELESAI])
