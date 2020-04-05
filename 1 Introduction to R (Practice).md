# Latihan

1. Perhatikan code berikut ini! Dapat dilihat code `install.packages()` menggunakan parameter character dengan adanya petik dua, sedangkan code `library` tidak. Apa yang menarik dari sini? (Jawaban bersifat terbuka, lakukan analisis bebas!)

    ```R
    install.packages("tidyverse")
    library(tidyverse)
    ```

2. Berikan contoh skenario pemanfaatan/pengelolaan *working directory* pada R? (Jawaban bersifat terbuka, lakukan analisis bebas!)

3. Uraikan permasalahan berikut ini
   - ( TRUE & TRUE ) | FALSE
   - ( TRUE | ( FALSE & FALSE ) ) & FALSE
   - FALSE | TRUE & FALSE
   - FALSE & TRUE | FALSE
   - ( FALSE & TRUE) | ( FALSE & FALSE)

4. Coba jalankan code di bawah ini
   - NULL == NA
   - NA == NaN
   - "1" == 1
   - ( pi < exp(1) ) | FALSE

5. Jika `sin(x)` adalah 1, maka berapakah `x`? (coba jalankan fungsi sin, cos, dan tan pada r)

6. Bagaimana cara menghapus sebuah variabel dari *global environment*?

7. Jelaskan beberapa fungsi matematika berikut!
   - `abs(x)`
   - `log(x, base = y)`
   - `exp(x)`
   - `sqrt(x)`
   - `factorial(x)`

8. Buatlah kode berdasarkan petunjuk berikut!

   - Sebuah bilangan `A` adalah hasil sisa pembagian 134789 dengan 253 dikali dengan hasil 'pembulatan ke atas' dari pembagian B dengan 7, di mana `B` adalah bilangan euler yang dipangkatkan 7.

   - `C` adalah sebuah variabel berjenis boolean yang bernilai `TRUE` apabila `A` adalah bilangan ganjil dan `FALSE` apabila bernilai genap. Lengkapilah kode berikut ini

     ```R
     # Cara 1
     if ( <<conditional>> ) {
         C  <-  <<boolean>>
     } else {
         C  <-  <<boolean>>
     }
     ```

     ```R
     # Cara 2
     C  <-  <<conditional>>
     ```

   - Berapakah nilai `A`, `B`, dan `C`?



