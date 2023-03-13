# chmod
Dosyalar için izin işlemlerini sağlar.

| Args | Açıklama |
| -------- | -------- |
| -v, --verbose | Detaylı bilgi verir. |
| --help | Yardım dökümanını verir. |
| --version | Versiyonu verir |

# Examples Commands

```sh
chmod 644		# -rw-r--r-- Owner okuma, yazma izni - Diğerleri okuma izni
chmod 666		# -rw-rw-rw- Herkes için okuma, yazma izni
chmod 700		# -rwx------ Owner okuma, yazma, çalıştırma izni
chmod 777		# -rwxrwxrwx Herkes için okuma, yazma, çalıştırma izni
```