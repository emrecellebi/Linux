# ls
Dosyalar hakkında bilgi ala bilmek için kullanılır.

| Args | Açıklama |
| -------- | -------- |
| -a, --all | Tüm dosya ve klasörleri listler.(Gizli) |
| -h, --human-readable | İnsan tarafından okuna bilir dosyaları listele |
| -i, --inode | Her dosyanın index numarasını yazar. |
| -l | Uzun formatta bir listeleme yapar.(Ayrıntılı) |
| -m | Klasörler ve dosyalar arasında virgül ile ayır. |
| -r, --reverse | Sırlama sırasında ters sıralama yapar |
| -s, --size | Her dosyanın boyutunu block halinde verir. |
| -t | Son Değiştirilmiş zamana göre sırala önce en yenisi. (Ayrıca --time)|
| --help | Yardım dökümanını verir. |
| --version | Verisiyonu verir. |

Ayrıntılı listeleme yaptığımız zaman bazı kısaltmaların olduğunu görürüz.

```
drwx — — — 35 ubuntu ubuntu 1120 Dec 27 19:54 Desktop
-rwxrw-r — 65 ubuntu ubuntu 1120 Dec 28 18:36 test.txt
lrwxr-x — — 65 ubuntu ubuntu 1120 Dec 28 18:36 file.lnk
```

| Komut | Açıklama |
| -------- | -------- |
| d | Dizin --> Directory |
| -	| Normal Dosya --> Regular File |
| l	| Sembolic link |
| r	| Okuma izni --> Read Permission |
| w	| Yazma izni --> Write Permisson |
| x	| Çalıştırma izni --> Execute Permisson |