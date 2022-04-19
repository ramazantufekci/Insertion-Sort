  # Insertion Sort Projesi
  
  [22,27,16,2,18,6] sıralanacak dizi örneğimizde

- Dizinin ikinci eleman başlangıç elemanı olarak seçilir.[22,**27**,16,2,18,6]

- Daha sonra 27 ile 22 kıyas edilir.27 22 den büyük olduğu için bir işlem yapılmaz daha sonraki elemana geçilir.
- 16 sayısı 27 den küçüktür bu yüzden 16 ikinci sıraya alınır.16<22 sayısından küçüktür en başa alınır.
- 2 sayısı 27 den küçüktür en başa alınır.
- 18 sayısı 27 den küçüktür 16 sayısından sonraya alınır
- 6 sayısı 27 küçüktür 2 ile 16 sayısı arasına alınır.Dizimizin son hali [2,6,16,18,22,27] olacaktır.  
                                                                              
 Big-O gösterimi N^2 olacaktır.
 
 18 case yapısı Worst case dir.
 
 [7,3,5,8,2,9,4,15,6] ilk 4 adımı
 
 - [7,**3**,5,8,2,9,4,15,6]
 - [3,**7**,5,8,2,9,4,15,6]
 - [3,5,**7**,8,2,9,4,15,6] 
 - [3,5,7,8,**2**,9,4,15,6] 
