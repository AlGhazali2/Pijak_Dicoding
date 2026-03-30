graph TD
    A[Mulai] --> B{Punya Data?}
    B -- Ya --> C[Preprocessing]
    B -- Tidak --> D[Cari Dataset]
    C --> E[Training Model ML]