# Introduction to R

(edit dikit)
- R
  - Cara akses R
    1. CMD
    2. R Command Line Interface
    3. IDE
  - Basic math + function
    1. Kalkulator
    2. Fungsi matematika dasar
  - Working with directory
    1. getwd()  :  melihat di mana working directory
    2. setwd()  :  mengatur working directory
    3. dir()      :  melihat file yang ada di working directory
    4. source()  : membuka file R (.r) biasanya rscript, (kayaknya bisa data dengan format tapi belum mastiin)
- R script
  1. rscript filename.r        -> dijalankan di CMD
  2. source("filename.r")     ->  dijalankan di dalam program R
- RStudio (IDE atau Integrated Development Environment)
  - 4 Bagian utama RStudio: 
    1. Console
    2. Workspace and history
    3. Files, plots, packages and help
    4. The R script(s) and data view
  - Default working directory
    - Tools > Global Setting > Set Working Directory
- R Programming Dasar
  - Atomic objects
    - Character
    - Numeric
    - Integer
    - Complex
    - Logical
  - Built-in Constant
  - Operator [^r-operators]
    - Arithmetic Operators
    - Relational Operators
    - Logical Operator
    - Assignment Operators
  - Variables
    1. Global vs Local Variabel (nanti aja deh)
    2. Aturan pemberian nama
       1. Tidak menggunakan reserved words
       2. Penggunaan angka, huruf, _underscore_, titik (karakter lain?)
    3. Penamaan variabel kalau ada dua kata atau lebih [^case-styles] [^case-styles-journal]
       1. snake_style
       2. camelStyle -> javascript
       3. snake-case -> html, css
       4. PascalStyle
  - Packages
    1. Install
         1. Install dari RStudio
         2. install.packages("package.name")
    2. Load
         1. library(package.name)
  - Environment
    1. ls()        :  Melihat semua variabel
    2. nama variabel yang diawali titik tidak terlihat di environment





[^r-operators]: *R Operators*, Data Mentor, https://www.datamentor.io/r-programming/operator/


[^case-styles-journal]: *The State of Naming Conventions in R*, 2012, Rasmus Bååth, https://journal.r-project.org/archive/2012-2/RJournal_2012-2_Baaaath.pdf
[^case-styles]: *Case Styles: Camel, Pascal, Snake, and Kebab Case*, 2018, Patrick Divine, https://medium.com/better-programming/string-case-styles-camel-pascal-snake-and-kebab-case-981407998841
