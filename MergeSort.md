# Merge Sort Projesi

[16,21,11,8,12,22]-> Merge Sort

 Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 
 
 1. Daha küçük parçalara ayırıp düzenlemek için ,sayı dizisini iki'ye bölüyoruz.




|Dizi iki ye bölünerek tekrardan yazılcak||||16|21|11|8|12|22||||
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

|Sol ve sağ taraf tekrardan ikiye bölünür|||16|21|11|||8|12|22|||
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

|Tek elemanın kalması için tekrar bölüyoruz||16||21|11|||8||12|22||
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

|Tek eleman olarak bu şekilde  |16||21||11|||8||12||22|
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

---
Bölme işlemi sonlandıktan sonra ikili birleştirmeler başlıyacaktır.Amaç sıralı dizi elde etmektir

---
|İkili gruplar halinde birleştirme yapılır||16||21|11|||8||12|22||
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|


|İkili gruplar halinde birleştirme tekrar edilir|||11|16|21|||8|12|22|||
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|


|Son aşamada birleşmiş dizimiz elde edilir||||11|16|21|8|12|22||||
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

## Big-O gösterimini yazınız.
O(nlogn)









