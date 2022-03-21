# myproject
***Yaptığım ilk proje***

## Basic Git Command
* ``` git init (repo oluşturmak için bir kez yapılır) ```
* ```git add [file.txt]&[.(all)] (Dosyaları eklemek için kullanırız.)```
* ```git rm [file.txt] (yazılı olan dosyayı siler.) ```
* ```git commit -m "first commit" (Bir head açar ve snapshot alır, tekrar geri dönülebilir.) ```
* ```git status (proje ile alakalı bilgiler verir.) ```
* ```git remote (uzak sunuculara, dosyaları göndermek için kullanılır)```
* ```git pull (projemizi veya dosyamızı uzak sunucudan makinemize çekmemize yarar)```

***Daha fazla bilgi için [Git-Cheat-Sheet](https://education.github.com/git-cheat-sheet-education.pdf)***

![resim](img\picture.PNG)

### Kısaca Git
>**Repository Proje dosyalarını uzak bir sunucuda depolar. Genel kullanımda “Repo” olarak da kısaltılır.**
Branch Projenin bir çok bölümünü derli toplu şekilde tutulmasını sağlar. Branchin avantajı ana branchteki(master) geliştirme yapısını etkilemeden projeyi diğer oluşturduğumuz branchler üzerinden yönetebiliriz.
**Master Reponun ana branchidir. Git üzerinde hiç bir işlem yapmazsak değişikler master branchi üzerinden devam eder.**
Commit Proje dosyalarınızda belli bir değişiklik yaptığınızda o değişikliğin anlık görüntüsünün alınıp kaydedilmesine denir.
**Checkout Mevcut branch üzerindeki commit’lerin üzerinde geçiş yapabilmemizi sağlar.**
Fork Repository’nin bir kopyasının alınmasıdır. Temel anlamda forkun kullanım amacı alınan bu kopya üzerinde değişiklikler yaptıktan sonra projenin ana reposuna gönderilerek projenin gelişmesine katkı sağlamaktır.
**Pull Request (PR): Fork edilen proje üzerinde değişiklikler yaptıktan sonra gerçek repository’e gönderilerek o projenin sahibi olan geliştiricinin değerlendirmesine sunmaktır. Eğer PR kabul edilirse ana repository üzerinde, fork ettiğiniz proje üzerinde değişiklikler işlenir.**
Merge Branch üzerinde yaptığımız değişiklikleri master branch’i üzerinde birleştirme işlemidir.


 