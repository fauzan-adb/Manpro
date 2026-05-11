# CSS
Objective : Menguasai styling dan layout dasar CSS
| Key Result        | Description                                                |
|-------------------|------------------------------------------------------------|
| KR1               | Memahami selector CSS dan cara menambahkan CSS ke HTML     |
| KR2               | Memahami properti styling dasar                            |
| KR3               | Memahami layout dasar                                      |

## 1) Memahami selector CSS dan cara menambahkan CSS ke HTML
Tujuan utama dari OKR ini adalah supaya saya mampu menghubungkan CSS ke HTML dan memilih elemen mana yang ingin diberi style.
## 1.1) Menambahkan CSS 
### a. Inline CSS
```
<p style="color: red;">Halo</p>
```
### b. Internal CSS
Didalam tag <style>.
```
<style>
  p {
    color: blue;
  }
</style>
```
### c. External CSS (yang paling penting)
HTML:
```
<link rel="stylesheet" href="style.css">
```
CSS :
```
p {
  color: green;
}
```
### Kenapa Penting?
Karena project nyata selalu pakai file CSS terpisah.

## 1.2) Memahami selektor
Selector = cara memilih elemen.

### a. Tag Selektor
```
p {
  color: red;
}
```
semua <p jadi merah.

### b. Class Selektor
HTML:
```
<p class="judul">Halo</p>
```
CSS:
```
.judul {
  font-size: 24px;
}
```

### c. ID Selektor
HTML:
```
<p id="utama">Halo</p>
```
CSS:
```
#utama {
  color: blue;
}
```
