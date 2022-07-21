# Mengenal CSS

## Inline CSS

Inline CSS diterapkan menggunakan attribute ```style="property:value;"``` di dalam tag pembuka html

```html
    <!-- Color -->
    <p style="color: blue;">CSS Colors</p>
```

```html
    <!-- Background -->
    <div style="background: blue;">
        CSS Background
    </div>
```

```html
    <!-- Border -->
    <div style="border: solid blue 1px;">
        CSS Borders
    </div>
```

```html
    <!-- Margin -->
    <div style="margin: 20px; background: yellow;">
        CSS Margin
    </div>
```

```html
    <!-- Padding -->
    <div style="padding: 20px;background: orange;">
        CSS Padding
    </div>
```



## Internal CSS

Internal CSS diterapkan dengan menempatkan code CSS di dalam elemen ```<style>...</style>``` diantara elemen ```<head>...</head>```

```html
<head>
    <!-- Code CSS -->
    <style type="text/css">
        body {
            background: black;
            color: white;
        }
        h1{
            color: red;
        }
        p{
            color: yellow;
        }

    </style>
</head>
```


## External CSS

External CSS diterapkan dengan menempatkan code CSS di dalam dokumen CSS secara terpisah dengan dokumen HTML. Misalkan dimasukan ke dalam file ```style.css```. Kemudian dihubungkan dengan menggunakan elemen ```<link href="namafolder/namafile.css">```

```html
<head>
    <!-- Menghubungkan Dokumen CSS -->
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
```


## Framework CSS Bootstrap

Framework CSS merupakan external CSS yang sudah dibuat atau dikembangkan oleh pihak lain, kemudian diterapkan ke dalam project kita.

Salah satu framework CSS adalah Bootstrap

Cara menghubungkan Framework CSS Bootstrap melalui Link CDN

```html
<head>
    <!-- Menghubungkan Framework CSS Bootstrap melalui CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
</head>
```

Cara menghubungkan Framework CSS Bootstrap yang sudah didownload

```html
<head>
    <!-- Menghubungkan file Framework CSS Bootstrap yang sudah didownload-->
    <link href="./css/bootstrap.min.css">
</head>
```