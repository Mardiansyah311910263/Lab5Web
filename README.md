# Praktikum 5
# Pemrograman Web
```
Mardiansyah
311910263
TI.19.C.1
Universitas Pelita Bangsa
```
## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
![P 5 1](https://user-images.githubusercontent.com/81758407/116433285-8d48dc80-a873-11eb-9cb3-be7915b63a35.PNG)
## Javascrip Dasar
Pemakaian Alert sebagai property window.
```
<html>
<head>
    <title>Alert box</title>
</head>
<body>
<script language = "javascript">
<!-- 
window.alert("Ini merupakan pesan untuk anda");
//-->
    </script>
</body>
</html>
```
![p 5 2](https://user-images.githubusercontent.com/81758407/116435868-05180680-a876-11eb-825d-b0579cd92de6.PNG)
Pemakaian method dalam objek
```
<html>
<head>
    <title>skrip javascript</title>
</head>
<body>
    Percobaan memakai javascript:<br>
<script language = "javascript">
<!-- 
 document.write("selamat mencoba javascript<br>");
 document.write("semoga sukses!");
//-->
    </script>
</body>
</html>
```
![p 5 3](https://user-images.githubusercontent.com/81758407/116436960-1e6d8280-a877-11eb-85a5-e01909b60497.PNG)
Pemakaian Prompt
```
<html>
<head>
    <title>Pemasukan data</title>
</head>
<body>
<script language = "javascript">
<!-- 
 var nama = prompt("siapa nama anda?","masukkan nama anda");
 document.write("hai,"+ nama);
//-->
    </script>
</body>
</html>
```
![p 5 4](https://user-images.githubusercontent.com/81758407/116437556-c3885b00-a877-11eb-80e5-9ee5bdbf101c.PNG)
Pembuatan fungsi dan cara pemanggilannya
```
<html>
<head>
    <title>contoh program javascript</title>
    <script language = "javascript">
        function pesan(){
            alert ("memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
</body>
</html>
```
![p 5 5](https://user-images.githubusercontent.com/81758407/116438357-912b2d80-a878-11eb-855e-f6b770442995.PNG)
## Dasar Pemrograman Di Javascript
Operasi dasar aritmatika
```
<html>
<head>
    <title>contoh program javascript</title>
    <script language = "javascript">
    function test (val1,val2)
    {
        document.write("<br>"+"perkalian : val1*val2"+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2"+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2"+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-al2"+"<br>")
        document.write(val1-val2) 
        document.write("<br>"+"modulus : val1%val2"+"<br>")
        document.write(val1%val2)  
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="aritmetic" onclick=test(9,4)>
</body>
</html>
```
![p 5 6](https://user-images.githubusercontent.com/81758407/116441288-858d3600-a87b-11eb-9f10-cd66d5973212.PNG)
Seleksi kondisi (if..else)
```
<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language = "javascript">
    <!--
        var nilai = prompt("nilai (0-100): ",0);
        var hasil = " ";
        if (nilai >= 60)
        hasil = "lulus";
        else hasil = "tidak lulus";
        document.write("hasil: " + hasil);
        //-->
    </script>
   </body>
</html>
```
![p 5 7](https://user-images.githubusercontent.com/81758407/116444347-d5b9c780-a87e-11eb-8224-1e93b0ed757e.PNG)
![p 5 8](https://user-images.githubusercontent.com/81758407/116444340-d3f00400-a87e-11eb-97f7-a4bf2a8eb12e.PNG)
Penggunaan operator switch untuk seleksi kondisi
```
<html>
<head>
    <title>contoh program javascript</title>

    <script language = "javascript">
    function test ()
    {
        vall=window.prompt("input nilai (1-5):")
        switch (vall)
        {
            case "1" :
                document.write("bilangan satu")
                break
            case "2" :
                document.write("bilangan dua")
                break
            case "3" :
                document.write("bilangan tiga")
                break
            case "4" :
                document.write("bilangan empat")
                break
            case "5" :
                document.write("bilangan lima")
                break
            default :
                document.write("bilangan lainnya")
        }
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```




