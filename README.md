# Kodluyoruz Veri Yapıları ve Algoritma Eğitimi

## Ödev 1 :   Selection Sort
-------------------------------

**[22,27,16,2,18,6] -> Insertion Sort**

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**1. Adım :** 
**22 | ,27 ,16 ,2 ,18 ,6**  ( 16 ile 27 sayıları karşılaştırılır, 27 sayısı 22 sayısından büyük olduğundan 22 'nin sağına yerleştirilir. )



**2. Adım :** 
**22 ,27 | ,16 ,2 ,18 ,6**  ( 27 ile 16 'yı karşılaştırılır, 16 sayısı 27 'den küçük olduğundan sola yazılır. Daha sonra 16 sayısı 22 'den de küçük olduğu için en başa yazılır. )



**3. Adım :** 
**16 ,22 ,27 | ,2 ,18 ,6**  ( 2 sayısı soldaki sayılarla karşılaştırılıp uygun yere yerleştirilir. )


**4. Adım :** 
**2 ,16 ,22 ,27 | ,18 ,6**  ( 18 sayısı sol taraftaki sayılarla karşılaştırılıp uygun yere yerleştirilir)


**5. Adım :** 
**2 ,16 ,18 ,22 ,27 |,6**  (6 sayısı da sol tarafta kalan sayılarla karşılaştırılıp uygun yere yerleştirilir.)


**6. Adım :**
**2 ,6 ,16 ,18 ,22 ,27**  ( Sıralı Bir Dizi Elde Edilir. )



## **Big O (n²)**

Time Complexity: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız

**Avarage Case** kapsamına girer. 

-----------------------------------------------------------
-----------------------------------------------------------
-----------------------------------------------------------

***[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.***


**1. Adım :**
[ **7** ,3 ,5 ,8 ,2 ,9 ,4 ,15 ,6]   ( Dizinin sonuna kadar bakılır 7 'den küçük sayı var mı? Varsa 7 ile yer değiştirilir. 7 ile 2 sayısı yer değiştirilir. )

**2. Adım :**
[ 2 , **3** ,5 ,8 ,7 ,9 ,4 ,15 ,6]   ( Sırada ki sayı ele alınır (3) 3 'den küçük sayı yok 3 aynen kalır. )

**3. Adım :**
[ 2 ,3 ,**5** ,8 ,7 ,9 ,4 ,15 ,6]   ( Sırada ki sayı ele alınır (5) Dizinin sonuna kadar bakılır 5 'den küçük sayı var mı? Varsa 5 ile yer değiştirilir. 5 ile 4 sayısı yer değiştirilir. )


**4. Adım :**
[ 2 ,3 ,4 , **8** ,7 ,9 ,5 ,15 ,6]   ( Sırada ki sayı ele alınır (8) Dizinin sonuna kadar bakılır 8 'den küçük sayı var mı? Varsa 8 ile yer değiştirilir. 8 ile 5 sayısı yer değiştirilir. )


**5. Adım :**
[ 2 ,3 ,4 , 5 , **7** ,9 ,8 ,15 ,6]  ............... Adımlar böyle devam eder. Dizi sıralı bir hale gelene kadar.