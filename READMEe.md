# Algoritma Perhitungan

## Deskritif

```
1. Mulai
2. Masukkan variabel A
3. Masukkan variabel B
4. Hitung Hasil dari A + B
5. Tampilkan Hasil
9. Selesai
```

## Flowchart

```mermaid
flowchart TD
    start((start))
    input1[/Input A/]
    input2[/Input B/]
    hasil[Hasil = A + B]
    output[/Tampilkan Hasil/]
    Finish(((end)))
    start --> input1 --> input2 --> hasil --> output --> Finish
```

## Pseudo-Code

```pseudo-code
DECLARE A : INTEGER

INPUT A

IF A > 10 THEN
    OUTPUT "ANGKA Lebih besar dari 10"
ELSEIF A >= 5 THEN
    OUTPUT "Angka lebih besar dari 5"
Else
    OUTPUT "Angka lebih kecil dari 10"
ENDIF
OUTPUT "Hasil nya adalah ", Hasil
```
