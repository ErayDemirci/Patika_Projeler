[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

**Time Complexity:** Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

**Average case:** Aradığımız sayının ortada olması
**Worst case:** Aradığımız sayının sonda olması
**Best case:** Aradığımız sayının dizinin en başında olması.




[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---

[22,27,16,2,18,6]

[22,27,16,2,18,6] **1. Adım:** İlk elemandan (22) önce kıyaslanacak bir eleman olmadığı için kontrole 2. elemandan (27) başlanır. Sıralama doğru olduğu için değişim yapılmaz. 
[16,22,27,2,18,6] **2. Adım:** 3. eleman (16) kendinden önceki elemanlardan (22 ve 27) küçük olduğu için ilk sıraya yazılır.
[2,16,22,27,18,6] **3. Adım:** 4. eleman (2) kendinden önceki elemanlardan (16, 22 ve 27) küçük olduğu için ilk sıraya yazılır.
[2,16,18,22,27,6] **4. Adım:** 5. eleman (18) kendinden önceki elemanlardan (22 ve 27) küçük olduğu için 3. sıraya yazılır.
[2,6,16,18,22,27] **5. Adım:** 6. eleman (6) kendinden önceki elemanlardan (16, 18, 22 ve 27) küçük olduğu için 2. sıraya yazılır.


Big-O Notation O(n²)--> n=6 => O(36)

Dizi sıralandıktan sonra 18 sayısı "Average Case" kapsamına girer.

---

[7,3,5,8,2,9,4,15,6] Dizisinin Selection Sort'a göre ilk 4 adımı:

[2,3,5,8,7,9,4,15,6] **1. Adım:** Dizideki en küçük eleman bulunur (2) ve ilk eleman (7) ile yer değiştirir.
[2,3,5,8,7,9,4,15,6] **2. Adım:** Sıralanmamış elemanlar içindeki en küçük eleman bulunur (3) ve 2. eleman ile yer değiştirir. Bu adımda 3 sayısı doğru konumda olduğu için yer değişimi yapılmaz.
[2,3,4,8,7,9,5,15,6] **3. Adım:** Sıralanmamış elemanlar içindeki en küçük eleman bulunur (4) ve 3. eleman (5) ile yer değiştirir.
[2,3,4,5,7,9,8,15,6] **4. Adım:** Sıralanmamış elemanlar içindeki en küçük eleman bulunur (5) ve 4. eleman (8) ile yer değiştirir.