# Elektriklər.org.az — GitHub Pages üçün professional statik sayt

Bu paket `elektrikler.org.az` domeni üçün hazırlanıb. Sayt problemsiz işləsin deyə əsas dizayn və JavaScript `index.html` daxilindədir. Ona görə ayrıca CSS/JS faylı yüklənməsə belə dizayn dağılmır.

## GitHub-da yükləmə qaydası

1. GitHub-da yeni repository aç: məsələn `elektrikler-az`.
2. Bu ZIP faylını kompüterdə çıxart.
3. Qovluğun içindəki faylları birbaşa repository root-a yüklə.
4. `index.html` mütləq root-da görünməlidir.

Düzgün struktur:

```text
elektrikler-az/
  index.html
  404.html
  CNAME
  .nojekyll
  robots.txt
  sitemap.xml
  site.webmanifest
  assets/
    favicon.svg
    img/
```

Səhv struktur:

```text
elektrikler-az/
  elektrikler_az_github_pro/
    index.html
```

## GitHub Pages aktiv etmə

Repository → Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: /root → Save.

## Domen qoşma

`CNAME` faylında artıq bu yazılıb:

```text
elektrikler.org.az
```

GitHub Pages-də Custom domain yerinə də `elektrikler.org.az` yaz.

Domen panelində GitHub Pages üçün DNS yazıları:

```text
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   elektrikgroup.github.io
```

Sonra GitHub Pages-də `Enforce HTTPS` aktiv et.

## Nəyi dəyişmək lazımdır?

Telefon/WhatsApp nömrəsi indi belədir:

```text
+994706545498
070 654 54 98
```

Dəyişmək üçün `index.html` faylında bu nömrələri axtarıb yenisi ilə əvəz et.

## Yeni şəkil əlavə etmək

1. Şəkli `assets/img/` qovluğuna yüklə.
2. Fayl adını boşluqsuz və Azərbaycan hərfsiz yaz: `menzil-isiqlandirma-01.jpg`.
3. `index.html` içində `Portfolio` bölməsində mövcud kartlardan birini kopyala və şəkil yolunu dəyiş.

## Qeyd

Saytda MMC, VÖEN və rəsmi şirkət iddiası yazılmayıb. Domen fiziki şəxs kimi alındıqda bu daha düzgündür. Gələcəkdə VÖEN açıldıqdan sonra footer və əlaqə bölməsinə əlavə edilə bilər.
