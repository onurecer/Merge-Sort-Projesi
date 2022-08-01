# Merge-Sort-Projesi

Merge Sort Project by www.patika.dev 

## [16,21,11,8,12,22] -> Merge Sort

### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* Dizi [16,21,11] ve [8,12,22] şeklinde ikiye bölünür.
* Daha sonra bunlar da [16,21] ve [11] ; [8,12] ve [22] şeklinde kendi içlerinde bölünür.
* Sonraki aşamada hepsi [16], [21], [11] ; [8], [12], [22] şeklinde ayrılır.
* Hepsi ayırıldıktan sonra karşılaştırılarak küçükten büyüğe sıralayarak birleştirme işlemi başlar:
* [16,21], [11] ve [8,12], [22] ==> 16 ile 21 ; 8 ile 12 karşılaştırıldı.
* [11,16,21] ve [8,12,22] ==> (16 ile 11 ; 21 ile 11) ve (8 ile 22 ; 12 ile 22) karşılaştırıldı.
* Son karşılaştırmalar yapılarak son hal [8,11,12,16,21,22] şeklinde bulunur.

### 2.Big-O gösterimini yazınız.

n, n/2 , n/4 şeklinde gittiğinden; 2^x = n eşitliğinden logn bulunur.

Her adımda da n sayıda işlem yapıldığından n bulunur.

O(nlogn)

        
        
   

