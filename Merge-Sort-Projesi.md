# Merge Sort
## [16,21,11,8,12,22] -> Merge Sort
### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1. Bölme (Divide)  
    * Diziyi iki alt diziye bölelim:  
    Sol Dizi: [16, 21, 11]  
    Sağ Dizi: [8, 12, 22]
2. Alt Dizileri Bölme
    * [16, 21, 11] dizisini ikiye bölelim:  
    Sol Dizi: [16]  
    Sağ Dizi: [21, 11]  
    * [8, 12, 22] dizisini ikiye bölelim:  
    Sol Dizi: [8]  
    Sağ Dizi: [12, 22]
3. Alt Dizileri Daha Da Bölme  

    * [21, 11] dizisini ikiye bölelim:  
Sol Dizi: [21]  
Sağ Dizi: [11]  

    * [12, 22] dizisini ikiye bölelim:  
        Sol Dizi: [12]  
        Sağ Dizi: [22]
4. Birleştirme (Merge)  
Şimdi sıralama işlemine başlıyoruz:

    * [21] ve [11]'i birleştirelim:  
    Sonuç: [11, 21]

    * [12] ve [22]'yi birleştirelim:  
    Sonuç: [12, 22]

    * [16] ve [11, 21]'i birleştirelim:  
    Sonuç: [11, 16, 21]

    * [8] ve [12, 22]'yi birleştirelim:  
    Sonuç: [8, 12, 22]

5. Son Birleştirme  
Son olarak, [11, 16, 21] ve [8, 12, 22] dizilerini birleştiriyoruz:

    * [8, 11, 12, 16, 21, 22]

### Big-O gösterimini yazınız.
  
* Average Case: O(n log n)  
* Worst Case: O(n log n)  
* Best Case: O(n log n)


