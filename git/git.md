Notes :  Tanımlar ve özellikler, ders notları, diğer notlar,  cheet sheet bulunmaktadır.

# TANIMLAR ve ÖZELLİKLER

Git Nedir?

Git free ve opernsource bir versiyon kontrol sistemidir.

kod daki değişiklikleri takip eden dağıtık bir sistemdir.

Git Ne işe yarar?

- Revert files to previous state,
- Revert entire project back to previous state,
- Compare changes over time,
- See who modified what? **And much more...**

Neden?

- Everything is local (full history tree available offline),
- Everything is fast,
- Snapshots, not diffs,
- It is distributed not centralized,
- Great for those who hate: CVS/SVN (earlier [version control systems](https://lms.clarusway.com/mod/lesson/view.php?id=642)).

VCS ne işe yarar?

- What had changed
- When it changed
- Why it changed
- Who changed it

Dosyaların saklanması gerekir. VCS kullanırsanız kaybetmezsiniz, tüm versiyonlarına erişebilirsiniz.

Populer versiyon kontrol sistemleri:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4f2a5f9d-f087-4c68-9f56-bc83cadbc40d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4f2a5f9d-f087-4c68-9f56-bc83cadbc40d/Untitled.png)

VCS in Önemi:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5c56190-59b8-4146-b0ef-48ed1ea5607e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5c56190-59b8-4146-b0ef-48ed1ea5607e/Untitled.png)

VCS Çeşitleri:

- File-based,        eski
- Client-server type,      git gibi
- Distributed.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/875d5240-7dad-44e1-bafd-3e1d5655426e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/875d5240-7dad-44e1-bafd-3e1d5655426e/Untitled.png)

Clien-Server tip iki çeşit:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9d5e0d7a-7453-4b69-91c1-471a4274235d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9d5e0d7a-7453-4b69-91c1-471a4274235d/Untitled.png)

Distributed sistemlerde her kullanıcı için bir kopya oluşturulur. Ağ bağlantısı kopsa bile devam eder.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/011f7b97-d43f-4574-84f9-f3b41b0344d8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/011f7b97-d43f-4574-84f9-f3b41b0344d8/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee63696d-cacd-4ae3-b9c8-2832926c4cee/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee63696d-cacd-4ae3-b9c8-2832926c4cee/Untitled.png)

Repository:

Projeler için dizin veya depolama alanı

Localde veya bulutta olabilir.

Git Takip Süreci:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2c9d8864-adc2-4557-8295-7896f6b10656/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2c9d8864-adc2-4557-8295-7896f6b10656/Untitled.png)

git repoda dosya 3 aşamada bulunabilir. Modified, Staged, and Committed.

- **Modified** means that you have changed the file but have not committed it to your database (repo) yet.
- **Staged** means that you have marked a modified file in its current version to go into your next commit snapshot.
- **Committed** means that the data is safely stored in your local database.

git projesinin 3 ana bölümü

- The working tree,
- The staging area,
- The Git directory.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/902dbcbc-8820-4be2-a9a9-3e671b02f4b2/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/902dbcbc-8820-4be2-a9a9-3e671b02f4b2/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aa190470-924e-4f0a-944a-f7edffbeb081/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aa190470-924e-4f0a-944a-f7edffbeb081/Untitled.png)

Alışveriş yapıyorsun sepete doldurdun sepet staging area. daha almadın değiştirebilirsin.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9e1297d-5f0d-41e9-a95a-92ef14cc58ba/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9e1297d-5f0d-41e9-a95a-92ef14cc58ba/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f330ead1-9d1f-4fb4-9038-4a74d8ee5cab/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f330ead1-9d1f-4fb4-9038-4a74d8ee5cab/Untitled.png)

# DERS NOTLARI

Git başlatma komutu:

$ git init

$ ls -al

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/970247de-f2c6-4223-8b76-2a20b51145fc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/970247de-f2c6-4223-8b76-2a20b51145fc/Untitled.png)

```
$ cd .git
$ ls -al
```

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/97c003fb-a3f5-4b4a-83cb-5ba6421aa610/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/97c003fb-a3f5-4b4a-83cb-5ba6421aa610/Untitled.png)

Örnek ;

1-) Takip etmek istediğin klasörü localde oluşturmaya başla. 

 $ touch index.html file.txt cprog.c javaprog.java index.js style.css type.ts
 $ ls –al

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/94d383af-cbe3-48af-8647-2c8465388a17/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/94d383af-cbe3-48af-8647-2c8465388a17/Untitled.png)

  

2-) Olışan klasörde takip sistemi yani git başlatma.

$ git init (o klasörde vcs başlatır)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a5178d4a-0e8b-4038-96c3-749a679f73dd/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a5178d4a-0e8b-4038-96c3-749a679f73dd/Untitled.png)

3-) Check git status.

  $ git status

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a2a082ed-2b55-4911-98e2-4de788e28a00/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a2a082ed-2b55-4911-98e2-4de788e28a00/Untitled.png)

kırmızılar çalışma alanında duruyor. git takip etmiyor

git status -s # Short status

4-) "Git add" to add the files to staging area from the working area.

  $ git add .

And now we can see the new status of the files.(Notice green color)

git add dosya_adı commite hazır.

  $ git status

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9c7eca9b-9343-4d25-999a-f15a1d7ce2a2/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9c7eca9b-9343-4d25-999a-f15a1d7ce2a2/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5207efe5-3666-4704-a575-f61c7426afa7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5207efe5-3666-4704-a575-f61c7426afa7/Untitled.png)

git  restore —staged dosya_Adı —>stage i geri alma

git rm --cached file1.js —>stage i geri alma

** git add yerine git rm de kullanılabilir.

5-) Let's commit our files to local repo with the command

`git commit –m "message/explanation"`

$ git commit –m “This folder includes demo files”

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f928babc-e4ca-4069-ab0c-de82ece1a837/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f928babc-e4ca-4069-ab0c-de82ece1a837/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10335e61-73dd-4e9f-a1a8-0eb51e196c6f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10335e61-73dd-4e9f-a1a8-0eb51e196c6f/Untitled.png)

git commit -am "message" direk değişiklikleri stage e atmadan commit etme. Dosya daha önce yaratılıp commit edildi ise çalışır. daha sonraki değişiklikler için add yapmadan commit yapılaiblilr.

git commit —amend  commit mesajı değiştirme.

** eğer uzun bir commit mesajı yazılacaksa -m yazılmaz editör açılır istediğiniz uzunlukta mesaj giriliebilir.

** tamamlanmamış değişikleri commit etmek yerine git stash ile kayıt altına alabilirsiniz.

git stash pop komutu ile yukarıdaki listenin en üstünde yer alan değişiklik geri yüklenecek ve bu değişiklik listeden silinecek.

git stash apply komutu ile istediğiniz değişikliği geri yükleyebilirsiniz. Ancak bu işlem sonrasında yüklediğiniz değişiklik listeden silinmeyecek.

Herhangi bir değişikliği listeden silmek için git stash drop komutunu kullanabilirsiniz.

Backuplama mantığı ve aynı dosya üzerinde birden fazla kişi çalışırsa doğabileccek sorunlar;

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4e7d45c7-160b-475f-a610-0edc231b62a1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4e7d45c7-160b-475f-a610-0edc231b62a1/Untitled.png)

1 ve 3 değişiklik yaptı remote a gönderdiğinde proje yöneticisi karar veriyor.

Konfigürasyon ayarları;

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/35e7127d-dddc-4f1e-90c2-6f32eadea938/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/35e7127d-dddc-4f1e-90c2-6f32eadea938/Untitled.png)

Working directory de bir değişiklik yapıldığında ;

git status yazınca kırmızı gözükecek

git add new_file2 yapınca stage area ya alır ve status yapınca yeşil olur.

birden fazla dosyayı aynı anda stage areaya koymak için git add . 

git add -u;

 değiştirilen ve silinen dosyaları staging areaya atmak için.

git log ;

yapılan tüm commitleri görebilen komut.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c8668f86-a5d3-4ec7-8b73-1d9bb28fd597/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c8668f86-a5d3-4ec7-8b73-1d9bb28fd597/Untitled.png)

sarı hash kodları ile commitleri takip edebilrisniz.

eski komuta gelmek için git checkot hash kodunun ilk 5 hanesini gir

git checkout ae0952e5

** git log -p detaylı logları görebilmeyi sağlar.

git checkout ile hem ileri hem de geri gelebilirsiniz.

HEAD hangi commit de olduğumuz ifade eder.

# GITHUB

GitHub is a Git repository hosting (Source Code Hosting) service

**What is the difference between Git and GitHub?**

Git is a version control system that lets you manage and keep track of your source code history locally. GitHub is a cloud-based hosting service that lets you manage Git repositories.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/20fafd43-8188-4eb7-9c17-cfccaae8b973/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/20fafd43-8188-4eb7-9c17-cfccaae8b973/Untitled.png)

git config

git config list ile config bilgilerini görebilirsiniz.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9bcb6bc4-6bbd-4a4c-88be-bab678c73166/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9bcb6bc4-6bbd-4a4c-88be-bab678c73166/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cefb4f6a-bb8a-41fe-b7fb-9ac6d6a43fbd/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cefb4f6a-bb8a-41fe-b7fb-9ac6d6a43fbd/Untitled.png)

BRANCH

Aynı projede birden fazla grup çalışması için herkes ayrı çalışıyor en sonda birleşecek.

hangi branch de iseniz head orayı gösterir.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2db8629b-43a3-4b24-91f2-9dc2dadbefb8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2db8629b-43a3-4b24-91f2-9dc2dadbefb8/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b02e60d7-f0a0-4b65-b8d2-6bbc0979e75f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b02e60d7-f0a0-4b65-b8d2-6bbc0979e75f/Untitled.png)

Branch komutları:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48c0eab5-d6b2-4c0a-a9c3-f25db50c5b99/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48c0eab5-d6b2-4c0a-a9c3-f25db50c5b99/Untitled.png)

git checkout -b newbranch3 yaratır ve geçer.

** git branch -v ile branchler hakkında ayrıntı gelir.

** Herhangi bir anda bir proje için tek bir branch aktif olabilir. Bu branch'e HEAD denir.

 ** git branch -dr superyeniozellik     —————-remote daki branch i silme

git push origin :superyeniozellik bu komut ile birlikte siler.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/82ee9f08-1d38-4552-abce-27f18be568bc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/82ee9f08-1d38-4552-abce-27f18be568bc/Untitled.png)

nerde iseniz ordaan birleştirmek istediğiniz yeri seçiyorsun

aynı dosya üzerinde farklı değişiklikler varsa conflict verir. bunu proje yöneticisi çözer.

bir grup hiç değişiklik yapmadan diğer kol yaparsa fast forward merge oluyor.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b2c4c9f-7245-4a28-806c-72927bc9adad/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b2c4c9f-7245-4a28-806c-72927bc9adad/Untitled.png)

git log --pretty=oneline 

git log --oneline 

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5838dda4-67f1-4dcc-9945-532212bf7cb9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5838dda4-67f1-4dcc-9945-532212bf7cb9/Untitled.png)

önce clone ile çek daha sonra pull ,le devam

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f8f5c1a7-7d76-441a-bee3-ed99bb541b74/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f8f5c1a7-7d76-441a-bee3-ed99bb541b74/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b15d003-3df2-4439-aeca-dce4cce08b6b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b15d003-3df2-4439-aeca-dce4cce08b6b/Untitled.png)

## UZAKTAKİ REPOYU(PRIVATE)  KENDİ GİTHUB IMIZA EKLEME

1-) Öncelikle bilgisayarınızda uygun bir yere klasör oluşturun. O klasöre uzaktaki repoyu clone edeceğiz.

2-)klasörün içinde iken git bash çalıştırıp 

git clone <uzak repo linki> komutunu çalıştırın.

dosyalar klasörünüze inmiş olacak.

Bu adımda yüklemek istediğimiz repoyu bilgisayara indirdik.

3-) Kendi Github hesabınızda yeni bir repo create edin. oluşan reponun url sini kopyalayın.

4-) git clone <uzak repo linki> komutunu çalıştırın.

dosyalar klasörünüze inmiş olacak.

Bu adımda boş yeni yarattığımız repoyu bilgisayara indirdik.

5-) 2 numaralı adımda oluşan dolu klasörün içindeki dosyaları .git hariç kopyalayıp 4. adımda oluşturduğumuz kendi  klaörümüze kopyalayın. Dikkat!! .git kopyalanmamalı.

6-) yapıştırdığımız yani kendi klasörümüzde dosyaları göndermeden önce add ve commit adımlarını yapmamız gerekiyor.

git add .

git commit -m "mesaj"

7-) dosya push edilmeye hazır.

git push

8-) sayfayı yeninediğinizde reponun dolduğunu görebilirsiniz.

.gitignore;

git in kontrol etmesini istemediğimiz dosyaları .gitignore klasörüne atılır.

# DİĞER NOTLAR

** md (markdown)  örn: readm.md

!! origin uzaktaki repo demek

git clone yapıldığında git init yapmaya gerek yoktur. Var olan bir repoyu bilgisayara çekme

Github genel komutlar;

echo "# starter" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SametUSTAOGLU/starter.

git push -u origin main

git remote -v  --> hangi repoda olduğunu gösterir.
git fetch --> uzaktaki değişikliği 
git pull  --> git fetch + git merge
git push origin newbranch cssnsnn.text --> yeni branchi remote a gönderme

vimden çıkış esc- :q!

git config core.autocrlf true uyarıları kapatmak için

git push origin master

[https://git-school.github.io/visualizing-git/](https://git-school.github.io/visualizing-git/) —> görsel commir-t brach çalışma sayfası.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/815f7827-3ba4-4579-8979-41496d0af46d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/815f7827-3ba4-4579-8979-41496d0af46d/Untitled.png)

origin aslında sağ taraftali linkin alias ı

git remote remove upstream  pul request için gönderdiğini silme

!! başka repoda olan değişiklikleri nasıl alabiliriz? 

git pull upstream main

!! farklı branhe geçip değişiklik yaptınız nasıl push edilecek.

git push yapınca hata alınır sebebi uzaktaki repoda  o branch yok

git push --set-upstream origin newbranch   

bu komut ile fork yaptığımız kendi repomuza gönderdik

son olarak repomuza girip yukarıdaki uyarıya tıklayıp creat pull request yapılacak.

** git merge --abort  — merge işlemi  geri alma.

** git rebase Branch-B  — merge gibi

Bu komut ile Git öncelikle Branch-A ile Branch-B'nin ortak en son commit'ini bulup ortak commit sonrasında Branch-A'da yapılan diğer tüm commit'leri geri alır. Aslında bu commitler silinmez sadece geçici olarak farklı bir yerde saklanır. Daha sonra Branch-B'deki tüm commitler Branch-A'ya uygulanır. Son aşamada ise Branch-A'nın geçici olarak farklı bir yerde saklanan commit'leri tekrar uygulanır. Bu işlemler sonrasında tüm değişiklikler sanki sadece Branch-A üzerinde gerçekleşmiş gibi görünür.

git config --global core.eol native
git config --global core.autocrlf true

       İPUCU: core.eol ve core.autocrlf değerleri Windows platformu için önerilen değerler. Git’in windows’da End-Of-Line karaketerlerini (Windows EOL için CRLF kullanıyor, Linux, Unix ve OSX ise LF kullanıyor) düzgün çalışması için global git konfigürasyonunuzda core.eol ve core.autocrlf ayarlarının yapılması gerekiyor. Ancak, proje depolarınızda .gitattributes dosyasının ilk satırında text=auto değerini girerseniz bu ayar yukarıda yapılan core.eol ve core.autocrlf ayarlarını ezecektir.

# GIT CHEATSHEET

## Initializing a repository

git init
Staging files
git add file1.js # Stages a single file
git add file1.js file2.js # Stages multiple files
git add *.js # Stages with a pattern
git add . # Stages the current directory and all its content

## Viewing the status

git status # Full status
git status -s # Short status

## Committing the staged files

git commit -m “Message” # Commits with a one-line message
git commit # Opens the default editor to type a long message

## Skipping the staging area

git commit -am “Message”

## Removing files

git rm file1.js # Removes from working directory and staging area
git rm --cached file1.js # Removes from staging area only

## Renaming or moving files

git mv file1.js file1.txt

## Viewing the staged/unstaged changes

git diff # Shows unstaged changes
git diff --staged # Shows staged changes
git diff --cached # Same as the above

## Viewing the history

git log # Full history
git log --oneline # Summary
git log --reverse # Lists the commits from the oldest to the newest

## Viewing a commit

git show 921a2ff # Shows the given commit
git show HEAD # Shows the last commit
git show HEAD~2 # Two steps before the last commit
git show HEAD:file.js # Shows the version of file.js stored in the last commit

## Unstaging files (undoing git add)

git restore --staged file.js # Copies the last version of file.js from repo to index

## Discarding local changes

git restore file.js # Copies file.js from index to working directory
git restore file1.js file2.js # Restores multiple files in working directory
git restore . # Discards all local changes (except untracked files)
git clean -fd # Removes all untracked files

## Restoring an earlier version of a file

git restore --source=HEAD~2 file.js

# Browsing History

## Viewing the history

git log --stat # Shows the list of modified files
git log --patch # Shows the actual changes (patches)

## Filtering the history

git log -3 # Shows the last 3 entries
git log --author=“Mosh”
git log --before=“2020-08-17”
git log --after=“one week ago”
git log --grep=“GUI” # Commits with “GUI” in their message
git log -S“GUI” # Commits with “GUI” in their patches
git log hash1..hash2 # Range of commits
git log file.txt # Commits that touched file.txt

## Formatting the log output

git log --pretty=format:”%an committed %H”

## Creating an alias

git config --global alias.lg “log --oneline"

## Viewing a commit

git show HEAD~2
git show HEAD~2:file1.txt # Shows the version of file stored in this commit

## Comparing commits

git diff HEAD~2 HEAD # Shows the changes between two commits
git diff HEAD~2 HEAD file.txt # Changes to file.txt only

## Checking out a commit

git checkout dad47ed # Checks out the given commit
git checkout master # Checks out the master branch

## Finding a bad commit

git bisect start
git bisect bad # Marks the current commit as a bad commit
git bisect good ca49180 # Marks the given commit as a good commit
git bisect reset # Terminates the bisect session

## Finding contributors

git shortlog

## Viewing the history of a file

git log file.txt # Shows the commits that touched file.txt
git log --stat file.txt # Shows statistics (the number of changes) for file.txt
git log --patch file.txt # Shows the patches (changes) applied to file.txt

## Finding the author of lines

git blame file.txt # Shows the author of each line in file.txt

## Tagging

git tag v1.0 # Tags the last commit as v1.0
git tag v1.0 5e7a828 # Tags an earlier commit
git tag # Lists all the tags
git tag -d v1.0 # Deletes the given tag

# Branching & Merging

## Managing branches

git branch bugfix # Creates a new branch called bugfix
git checkout bugfix # Switches to the bugfix branch
git switch bugfix # Same as the above
git switch -C bugfix # Creates and switches
git branch -d bugfix # Deletes the bugfix branch

## Comparing branches

git log master..bugfix # Lists the commits in the bugfix branch not in master
git diff master..bugfix # Shows the summary of changes

## Stashing

git stash push -m “New tax rules” # Creates a new stash
git stash list # Lists all the stashes
git stash show stash@{1} # Shows the given stash
git stash show 1 # shortcut for stash@{1}
git stash apply 1 # Applies the given stash to the working dir
git stash drop 1 # Deletes the given stash
git stash clear # Deletes all the stashes

## Merging

git merge bugfix # Merges the bugfix branch into the current branch
git merge --no-ff bugfix # Creates a merge commit even if FF is possible
git merge --squash bugfix # Performs a squash merge
git merge --abort # Aborts the merge

## Viewing the merged branches

git branch --merged # Shows the merged branches
git branch --no-merged # Shows the unmerged branches

## Rebasing

git rebase master # Changes the base of the current branch

## Cherry picking

git cherry-pick dad47ed # Applies the given commit on the current branch

# Collaboration

## Cloning a repository

git clone url

## Syncing with remotes

git fetch origin master # Fetches master from origin
git fetch origin # Fetches all objects from origin
git fetch # Shortcut for “git fetch origin”
git pull # Fetch + merge
git push origin master # Pushes master to origin
git push # Shortcut for “git push origin master”

## Sharing tags

git push origin v1.0 # Pushes tag v1.0 to origin
git push origin —delete v1.0

## Sharing branches

git branch -r # Shows remote tracking branches
git branch -vv # Shows local & remote tracking branches
git push -u origin bugfix # Pushes bugfix to origin
git push -d origin bugfix # Removes bugfix from origin

## Managing remotes

git remote # Shows remote repos
git remote add upstream url # Adds a new remote called upstream
git remote rm upstream # Remotes upstream

# Rewriting History

## Undoing commits

git reset --soft HEAD^ # Removes the last commit, keeps changed staged
git reset --mixed HEAD^ # Unstages the changes as well
git reset --hard HEAD^ # Discards local changes

## Reverting commits

git revert 72856ea # Reverts the given commit
git revert HEAD~3.. # Reverts the last three commits
git revert --no-commit HEAD~3..

## Recovering lost commits

git reflog # Shows the history of HEAD
git reflog show bugfix # Shows the history of bugfix pointer

## Amending the last commit

git commit --amend

## Interactive rebasing

git rebase -i HEAD~5
