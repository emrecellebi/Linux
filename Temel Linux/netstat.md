# netstat
Çalışan servisleri verir.

| Args | Açıklama |
| -------- | -------- |
| -n, --numeric |  |
| -p, --programs | Soket kullanan programların isim/pid verir. |
| -l, --listening | Dinlenilen soketleri verir. |
| -u, --udp | UDP bağlantılarını verir. |
| -t, --tcp | TCP bağlantılarını verir. |
| -v, --verbose | Detaylı bilgi verir. |
| --help | Yardım dökümanını verir. |

# Example Commands
```sh
netstat -t				# TCP Bağlantısını getir.
netstat -u				# UDP Bağlantısını getir.
netstat -l				# Listening soketler
netstat -p				# Soket kullanan progralar
netstat -n				# 
```