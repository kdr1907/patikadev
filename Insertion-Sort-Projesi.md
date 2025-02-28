## Insertion Sort Projesi

## [22,27,16,2,18,6] -> Insertion Sort  

### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.  

1. Dizi: [22, 27, 16, 2, 18, 6]
2. 16, 22 ve 27'den küçük olduğundan başa taşınır: [16, 22, 27, 2, 18, 6]
3. 2, hepsinden küçük olduğundan başa taşınır: [2, 16, 22, 27, 18, 6]
4. 18, doğru pozisyona yerleştirilir: [2, 16, 18, 22, 27, 6]
5. 6, doğru pozisyona yerleştirilir: [2, 6, 16, 18, 22, 27]
- Sonuç: Sıralı dizi: [2, 6, 16, 18, 22, 27]  

### Big-O gösterimini yazınız.

- Average Case: O(n^2)
- Worst Case: O(n^2)
- Best Case: O(n)

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
18 sayısı, "Average Case" kapsamına girer çünkü sıralama işlemi ortalama durumda gerçekleştiğinde, 18 genellikle dizinin ortalarında yer alır.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Sıralama Adımları (İlk 4 Adım)

- [7, 3, 5, 8, 2, 9, 4, 15, 6]  
1. [2, 3, 5, 8, 7, 9, 4, 15, 6] (2 başa alınır)  
2. [2, 3, 5, 8, 7, 9, 4, 15, 6] (3 zaten doğru yerde)  
3. [2, 3, 5, 8, 7, 9, 4, 15, 6] -> [2, 3, 4, 8, 7, 9, 5, 15, 6] (4 ile 5 yer değiştirir)  
4. [2, 3, 4, 8, 7, 9, 5, 15, 6] -> [2, 3, 4, 5, 7, 9, 8, 15, 6] (5 ile 8 yer değiştirir)  
* Bu sıralama yöntemi, "seçmeli sıralama" (selection sort) olarak bilinir. Her adımda, geri kalan dizinin en küçük elemanını bulup doğru pozisyona yerleştirir.