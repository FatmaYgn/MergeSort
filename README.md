# MergeSort

Merge Sort, diziyi bölme ve sonra birleştirme prensibine dayanan bir sıralama algoritmasıdır.
**Başlangıç Dizisi**
`[16, 21, 11, 8, 12, 22]`
1. **Adım**
`[16, 21, 11] ve [8, 12, 22]`
2. **Adım**
```Her bir alt dizi tekrar ortasından bölünür:
[16] ve [21, 11]
[21] ve [11]
[8] ve [12, 22]
[12] ve [22]
Artık alt diziler şunlardır: [16], [21], [11], [8], [12], [22]
```
3. **Adım**
```Alt diziler, sıralı bir şekilde birleştirilir:
Alt diziler, sıralı bir şekilde birleştirilir:

[21] ve [11]:

Birleştir: [11, 21]
[16] ve [11, 21]:

Birleştir: [11, 16, 21]
[12] ve [22]:

Birleştir: [12, 22]
[8] ve [12, 22]:

Birleştir: [8, 12, 22]
Son olarak, [11, 16, 21] ve [8, 12, 22] dizilerini birleştir:
```
**Sonuç**
`Dizinin sıralanmış hali: [8, 11, 12, 16, 21, 22]`

## Big-O Notation Gösterimi
- En kötü durumda: O(n log n)
- En iyi durumda: O(n log n)
- Ortalama durumda: O(n log n)