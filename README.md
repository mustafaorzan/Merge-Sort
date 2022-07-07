# Merge-Sort

patika.dev -> https://app.patika.dev/cataldirect

[16,21,11,8,12,22] -> Merge Sort

1 - Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

    [16,21,11,8,12,22]
    
    [16,21,11] v [8,12,22]  -> // v: Ortadan böldüğümden dolayı ayraç olarak kullandım. Mantıksal operatör değildir (veya gibi ya da versus gibi)!!!
    
    [16,21] [11] v [8,12] [22] -> n/2 den 1.5 (bir buçuk) çıkıyor ancak ilk 2 elemanı 1 dizide(kümede) tutup kalanı tek dizide(kümede) bıraktım
    
    [16] [21] [11] v [8] [12] [22]
    
    [16,21] [11] v [8,12] [22] -> Sıralama ve Birleşimin başladığı yer
    
    [11,16,21] v [8,12,22]
    
    [8,11,12,16,21,22] <- Sonuç

2 - Big-O gösterimini yazınız.
    
    merge sort un big-o gösterimi O(n log n). 
    
    Best, Worst ve Average case lerdeki big o gösterimi aynıdır. 
    
    n = 6 elemanım var benim o zaman big o gösterimim
    o(6 log 6) yapar
