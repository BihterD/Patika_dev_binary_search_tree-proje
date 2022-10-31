# Patika_dev_binary_search_tree-proje

### Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root: 7
root elemanı 7 olduğu için 7'den küçük olanlar ağacın sol tarafına büyük olanlar ise sağ tarafına yerleştirilir. Diğer elemanlar da benzer şekilde karşılaştırıldığı elemanlarca ağacın sağında ve solunda yer alır.
             7
        5          8
    1       6          9
 0     3
    2     4
    
    -5, 7'den küçük olduğu için solda 8 büyük olduğu için sağda yer aldı.
    -1, 7'den ve 5'den küçük olduğu için her ikisinin solunda yer aldı.
    -3, 7 ve 5'den küçük olduğu için bunların solunda 1'den büyük olduğu için 1'in sağında yer aldı.
    -6, /'den küçük olduğu için solda ancak 5'den büyük olduğu için sağında yer aldı.
    -0, hepsinden küçün olduğu için solda yer aldı.
    -9, 7 ve 8'den büyük olduğu için ağacın en sağında yer aldı.
    4, 3'den büyük olduğu için 3'ün sağında, 2 ise küçün olduğu için 3'ün solunda yer aldı.
    
    
    https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje
