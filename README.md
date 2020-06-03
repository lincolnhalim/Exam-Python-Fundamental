# Soal Ujian Python Data Science Fundamental

![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

#

### **Soal 1 - Kategori Bilangan (15 poin)**

Buatlah sebuah __file python__ yang dapat mengkategorikan suatu angka.
Kategori Angka yang akan digunakan antara lain :

- __Bilangan Negatif__: Himpunan bilangan bulat yang nilainya lebih kecil dari 0, yaitu (-1, -2, -3, ...)

- __Bilangan Nol__: Yaitu 0

- __Bilangan Ganjil__: Himpunan bilangan asli positif yang nilainya tidak habis dibagi 2, yaitu (1, 3, 5, 7, 9, ...)

- __Bilangan Genap__: Himpunan bilangan asli positif yang nilainya habis dibagi 2, yaitu (2, 4, 6, 8, 10, ...). Bilangan nol (0) juga digolongkan sebagai bilangan genap.

- __Bilangan Prima__: Himpunan bilangan asli yang nilainya lebih besar daripada 1, yang faktor pembaginya adalah 1 dan bilangan itu sendiri. 2 dan 3 adalah bilangan prima. 4 bukan bilangan prima karena dapat dibagi 2.

- __Bilangan Komposit__: Himpunan bilangan asli yang nilainya lebih besar daripada 1, yang bukan merupakan bilangan prima.

- __Case Flow__: Saat dieksekusi, program akan meminta user memasukkan angka secara bebas. Kemudian user akan mendapatkan kategori bilangan dari angka yang dimasukkan, dalam bentuk __list__.

- Output yang diharapkan saat file diekseskusi via terminal:
  
  ```bash
  Ketik angka : 2
  Bilangan tersebut termasuk bilangan ['genap', 'prima']

  Ketik angka : 15
  BIlangan tersebut termasuk bilangan ['ganjil', 'komposit']
  
  Ketik angka : 7
  Bilangan tersebut termasuk bilangan ['ganjil', 'prima']
  ```

- __Condition__: Program hanya menerima angka bulat, jika user memasukkan __bilangan desimal__ maupun memasukkan __string__ akan keluar notifikasi :

  ```bash
  Ketik angka : ujian
  Anda memasukkan kata bukan angka, silakan coba lagi!

  Ketik angka : 20.5
  Anda memasukkan bilangan desimal, silakan coba lagi!
  ```
  
_**Catatan:**_ _Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __Kategori_Bilangan__.
Kemudian lampirkan __url link repo Github__ Anda via email (BSD & Bandung) ke khumaeni@purwadhika.com dan (Jakarta) ke nurrokim@purwadhika.com_


#

### **Soal 2 - Konversi Waktu (15 Poin)**

Buatlah sebuah __return function__ dengan __1 argumen__ yang akan menerima inputan __bilangan integer(Seconds)__.
Dan akan menghasilkan output __string__ dengan format waktu ("HH:MM:SS").

- __HH__ : Hours, 2 digits, range: 00 - 99
- __MM__ : Minutes, 2 digits, range: 00 - 59
- __SS__ : Seconds, 2 digits, range: 00 - 59

- __Case Flow__: Saat dieksekusi, program akan mencetak nilai return function.


  ```python
  def timeConverter(seconds):
        .....
   
  
  Masukkan detik : 3600
  Konversi : 01:00:00

  Masukkan detik : 3665
  Konversi : 01:01:05
  ```
  
- __Condition__: Program hanya menerima angka bulat, dengan __nilai maksimal 359999__, jika user memasukkan __nilai lebih dari itu__, __bilangan desimal__ , __bilangan negatif__, maupun memasukkan __string__ akan keluar notifikasi. __Invalid Input__

  ```bash
  Masukkan detik : ujian
  Invalid Input!

  Masukkan detik : 20.5
  Invalid Input!
  ```
_**Catatan:**_ _Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __Konversi_Waktu__.
Kemudian lampirkan __url link repo Github__ Anda via email (BSD & Bandung) ke khumaeni@purwadhika.com dan (Jakarta) ke nurrokim@purwadhika.com_

#

### **Soal 3 - Mengurai dan Merajut Kata (20 Poin)**


Buatlah sebuah __file python (*.py*)__ yang berisi __2 buah return function__, dengan __1 argumen__ yang dapat digunakan untuk mengurai & merajut sebuah __string__.

```python
    def urai(...):
        ...
    def rajut(...):
        ...
```

- fungsi __urai(...)__ akan mengurai string. contoh output yang diharapkan adalah sebagai berikut:

    ```python
    print(urai('Code'))
    print(urai('Python'))
    print(urai('Purwadhika'))

    # Output:
    CCoCodCode
    PPyPytPythPythoPython
    PPuPurPurwPurwaPurwadPurwadhPurwadhiPurwadhikPurwadhika
    ```

- Sedangkan fungsi __rajut(...)__ akan merajut kembali string yang terurai menjadi bentuk kata asalnya. contoh output yang diharapkan adalah sebagai berikut:

    ```python
    print(rajut('CCoCodCode'))
    print(rajut('PPyPytPythPythoPython'))
    print(rajut('PPuPurPurwPurwaPurwadPurwadhPurwadhiPurwadhikPurwadhika'))
    
    # Output:
    Code
    Python
    Purwadhika
    ```
_**Catatan:**_ _Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __Urai_Rajut_Kata__.
Kemudian lampirkan __url link repo Github__ Anda via email (BSD & Bandung) ke khumaeni@purwadhika.com dan (Jakarta) ke nurrokim@purwadhika.com_

#

### **Soal 4 - List Spinner (20 Poin)**

Buatlah sebuah __file python__ yang dapat memutar __list angka__ .
- __List awal__
    ```bash
    [1, 2, 3]
    [4, 5, 6]
    [7, 8, 9]
    ```
 -__List Ouput__
     ```bash
    [3, 6, 9]
    [2, 5, 8]
    [1, 4, 7]
    ```
_**Catatan:**_ _Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __List_Spinner__.
Kemudian lampirkan __url link repo Github__ Anda via email (BSD & Bandung) ke khumaeni@purwadhika.com dan (Jakarta) ke nurrokim@purwadhika.com_


#

### **Soal 5 - Segitiga Kata (30 Poin)**

Buatlah __sebuah file python__ (*.py*) yang mengandung __sebuah function__ dengan __1 argumen__, yang dapat membentuk pola segitiga dengan elemen berupa karakter-karakter dari sebuah __string__ yang menjadi argumen function tersebut.

- __Case Flow__: Saat dieksekusi, program akan mencetak pola segitiga dari karakter-karakter string yang diinputkan. Jika jumlah karakter string memenuhi syarat terbentuknya pola, maka program akan menjalankannya. Namun jika jumlah karakter string tidak memenuhi syarat membentuk pola, maka akan muncul pesan bahwa string tidak memenuhi syarat membentuk pola.

    ```python
    segitigaKata('Purwadhika')
    segitigaKata('Purwadhika Startup and Coding School @BDG')
    segitigaKata('kode python')
    segitigaKata('kode')
    ```

- __Output__ yang diharapkan:
  
    ```bash
    # segitigaKata('Purwadhika')
    P 
    u r     
    w a d   
    h i k a 
    p u r w 
    a d h   
    i k     
    a   

    # segitigaKata('Purwadhika Startup and Coding School @BDG')
    P
    u r
    w a d 
    h i k a
    S t a r t
    u p a n d C
    o d i n g S c
    h o o l @ B D G
    P u r w a d h i
    k a S t a r t
    u p a n d C
    o d i n g
    S c h o
    o l @
    B D 
    G



    # segitigaKata('kode python')
    k
    o d
    e p y
    t h o n
    k o d e
    p y t
    h o
    n
    
    # segitigaKata('kode')
    Mohon maaf, jumlah karakter tidak memenuhi syarat membentuk pola.

    ```


_**Catatan:**_ _Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __Segitiga_Kata__.
Kemudian lampirkan __url link repo Github__ Anda via email (BSD & Bandung) ke khumaeni@purwadhika.com dan (Jakarta) ke nurrokim@purwadhika.com_


#

### *__#Good Luck & HappyCoding__* 
