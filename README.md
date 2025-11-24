# Liverpool Transfers (2004–2024)

## Kako pokrenuti
1) U root folderu napravite `.env` sa: API_FOOTBALL_KEY=VAŠ_KLJUČ
2) Instalirajte pakete: `pip install -r requirements.txt` (može i u Anacondi).
3) Otvorite Jupyter, pokrenite `liverpool_transfers.ipynb` ćeliju po ćeliju ali tu je 
   potrebno promeniti vrednosti "project_root" sa putanjom na kojoj želite da Vam se kreiraju folderi
4) CSV izlazi su u `data_raw/` i `data_processed/`, slike u `figures/`.

## Struktura grafa
- Node = klub
- Edge = transfer (usmeren)
- Težina ivica: `transfers_count`(izabrana), `total_fee_eur`, `count_transfer/loan/free`, `avg_fee_eur`

## Gephi
- Import: `data_processed/liverpool_transfers.graphml`
- Potebno je izabrati orijentisani graf prilikom izbora
- Sa leve strane u layout bira se ForceAtlas2 i igra sa scalling i gravity (preporucljivo do 1.0) i klikne start,
  zatim se pusti da se krece graf i kad se svidii polozaj nodova onda kliknuti na stop
- Takodje sa leve strane u Appearance moze se modifikovati graf.
- Izvestaj projekta ce sadrzati sliku grafa tako da to je opcija samo ako zelite da pomenite izgled grafa u Gephi :) 