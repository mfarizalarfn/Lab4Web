# Lab4Web

**Nama  : Mohamad Farizal Arifin**

**Nim   : 312010231**

**Kelas : TI.20.B.1**

<br>

**Langkah - langkah praktikum**<br>

1. membuat dokumen HTML dengan nama file **lab4_box.html** seperti berikut.<br>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Element</title>
</head>
<body>
    <header>
        <h1>Box Element</h1>
    </header>
</body>
</html>
```
<br>

2. Membuat Box Element <br>
Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut.<br>

```
<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
</section>
```
<br>

3. CSS Float Property <br>
Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut.<br>

```
<style>
    div {
        float:left;
        padding: 10px;
    }
    .div1 {
        background: red;
    }
    .div2 {
        background: yellow;
    }
    .div3 {
        background: green;
    }
</style>
```
<br>
Kemudian buka browser untuk melihat hasilnya. <br>
Berikut hasilnya :<br>
<br>

![gambar 1](image/pict1.PNG) <br>
<br>

4. Mengatur Clearfix Element <br>
**Clearfix** digunakan untuk mengatur element setelah float element. Property clear digunakan untuk mengaturnya.<br>
Tambahkan element div lainnya seteleah div3 seperti berikut.<br>

```
<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
    <div class="div4">Div 4</div>
</section>
```
<br>
Kemudian atur property clear pada CSS, seperti berikut.<br>

```
.div4 {
    background-color: blue;
    clear: left;
    float: none;
}
```
<br>
Selanjutnya buka browser dan refresh kembali. <br>
<br>

![gambar 2](image/pict2.PNG) <br>
<br>