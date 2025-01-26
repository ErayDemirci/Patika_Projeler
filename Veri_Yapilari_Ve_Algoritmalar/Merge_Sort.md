[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

---

**1. Adım:** [16,21,11,8,12,22]--> [16,21,11] ve [8,12,22] her eleman tek kalana kadar ikiye ayırma işlemi gerçekleşir.

**2. Adım:** [16,21,11]--> [16,21], [11] ve [8,12,22]--> [8,12], [22]

**3. Adım:** [16,21], [11]--> [16],[21],[11] ve [8,12], [22]--> [8], [12], [22]

**4. Adım:** [16,21], [11] ve [8,12], [22] Sıralayarak birleştirme işlemi gerçekleşir.

**5. Adım:** [11,16,21] ve [8,12,22]

**6. Adım:** [8,11,12,16,21,22] Şeklinde sıralama işlemi tamamlanır.

Big-O Notation O(n\*log n)--> n=6, log₂6=2.58≈3 => O(6\*log6) => O(6*3)=O(18)