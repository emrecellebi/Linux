# apt-get
Paket yükeleyicisi

| Args | Açıklama |
| -------- | -------- |
| install | Paketi yükle |
| reinstall | Paketi yeniden yükle |
| remove | Paketi sil |
| autoremove | Paketi otomatik sil |
| update | Listedeki paketleri güncelle |
| upgrade | Systemdeki paketleri yükle/güncelle |
| clean | Archive dosylarını temizle |
| autoclean | Archive dosylarını otomatik temizle |
| --help | Yardım dökümanı verir. |

```sh
apt-get upgrade --fix-missing			# Paket yüklerken hata alınsa bile yine de yükle.
```