edited

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ git --version
git version 2.34.1.windows.1

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ git config --global user.name Orley

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ git config --global user.email mbe.orley@yandex.ru

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ git config --global color.ui auto

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Orley
user.email=mbe.orley@yandex.ru
color.ui=auto

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd Downloads/

Asus@DESKTOP-4AEEPNB MINGW64 ~/Downloads
$ mkdir TestDir

Asus@DESKTOP-4AEEPNB MINGW64 ~/Downloads
$ ls
 2098__-_-S01-09-2011.torrent
 654_Shadows_Awakeni.torrent
 782_Pro_Evolution_S.torrent
 7z1900-x64.exe*
 7z2102-x64.exe*
 7z2102.exe*
 836_Dragon_Age_II_b.torrent
 846_Assetto_Corsa_b.torrent
 AdobePhotoshop_Rus.exe*
'Firefox Installer.exe'*
 Game.of.Thrones.S01-07.LostFilm.AlexFilm.Dub.En_22140.torrent
'Microsoft Office 2013_OfficeApache.exe'*
 R.A.W._-_Realms_of_Ancient_War.torrent
'SF-Helper-[cacab7a181f0f087#399#].exe'*
 Sacred_3_Steam-Rip.torrent
 Stranger_Things_s01_33470.torrent
 Stranger_Things_s02_33470.torrent
 Stranger_Things_s03_33471.torrent
 TestDir/
 The-Incredible-Adventures-of-Van-Helsing-II.torrent
 The-Incredible-Adventures-of-Van-Helsing-III.torrent
'[SW.BAND] [Дмитрий Черемушкин] Стратегический вебинар по российским акциям. Сентябрь (2021).zip'
'[SW.BAND] [Роман Андреев] Как искать тренды и развороты на рынке (2021).zip'
 age-of-empires-ii-definitive-edition-by-xatab.torrent
 age_of_empires_2_definitive_edition.torrent
 batman-arkham-knight-by-xatab.torrent
 batman-arkham-knight-game-of-the-year-edition.torrent
 batman_the_enemy_within_noir-gog_37813_win_gog.torrent
'bound_by_flame_2195b_32605_win_gog (1).torrent'
 bound_by_flame_2195b_32605_win_gog.torrent
 car-mechanic-simulator-2018-by-xatab.torrent
 cities-skylines-v_1_13_3-f9-2015.torrent
 desktop.ini
 devil-may-cry-5-by-xatab.torrent
 divinity_original_sin_2_3_6_69_4648a_46471_win_gog.torrent
 dragon_age_origins_1_5_2_1_0_4_win_gog.torrent
 final-fantasy-trilogy-iiiiii-pixel-remaster.torrent
 grand-theft-auto-v-1_0_2372-rockstar-rip.torrent
 microsoft-office.torrent
 prince_of_persia_warrior_within_1_00_999-v2_28549_win_gog.torrent
 serious-sam-4-by-xatab.torrent
 serious-sam-4.torrent
 sherlock_holmes_the_devils_daughter_updated-version_47726_win_gog.torrent
 tcmd1000x64.exe*
 total-war-warhammer-ii-by-xatab.torrent
 uTorrent.exe*
 victor-vran.torrent
'Волк с Уолл-стрит  The Wolf of Wall Street (2013) BDRip-AVC _ D.torrent'
'Омерзительная восьмерка - The Hateful Eight (2015) BDRip-AVC от New-Team  Лицензия.torrent'
'Омерзительная восьмерка - The Hateful Eight (2015) WEB-DLRip _ КПК _ P _ Extended Cut.torrent'
'Расписание 1к _веч_октябрь.docx'
'Скрытые фигуры - Hidden Figures (2016) BDRip от MegaPeer _ Лицензия.torrent'
'Скрытые фигуры - Hidden Figures (2016) HDRip от Scarabey _ Лицензия.torrent'
'Эк пред_Теор часть 1.pdf'
'Эк пред_Теор часть 2.pdf'
'пособие ТФ Писаренко.pdf'

Asus@DESKTOP-4AEEPNB MINGW64 ~/Downloads
$ cd TestDir

Asus@DESKTOP-4AEEPNB MINGW64 ~/Downloads/TestDir
$ cd ../..

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ touch test.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 test.txt
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cp test.txt test_copy.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 test.txt
 test_copy.txt
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ mv test.txt test_original.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 test_copy.txt
 test_original.txt
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd test-github
bash: cd: test-github: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd projects
bash: cd: projects: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 test_copy.txt
 test_original.txt
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd test-github
bash: cd: test-github: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd projects
bash: cd: projects: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ /c
bash: /c: Is a directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ echo "hello"
hello

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ echo "hello" > test_original.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cat test_original.txt
hello

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ rm test_original.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 test_copy.txt
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ /c
bash: /c: Is a directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ make projectdir
bash: make: command not found

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ mkdir project

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ touch changes.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ touch readme.md

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 changes.txt
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 project/
 readme.md
 test_copy.txt
'Мои документы'@
 Шаблоны@
'главное меню'@

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd project

Asus@DESKTOP-4AEEPNB MINGW64 ~/project
$ touch changes.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/project
$ readme.md
bash: readme.md: command not found

Asus@DESKTOP-4AEEPNB MINGW64 ~/project
$ touch readme.md

Asus@DESKTOP-4AEEPNB MINGW64 ~/project
$ ls
changes.txt  readme.md

Asus@DESKTOP-4AEEPNB MINGW64 ~/project
$ cd Desktop
bash: cd: Desktop: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~/project
$ cd ..

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd Dekstop
bash: cd: Dekstop: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~
$ cd Desktop

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop
$ mkdir repo

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop
$ cd repo

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo
$ ls

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo
$ git init
Initialized empty Git repository in C:/Users/Asus/Desktop/repo/.git/

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls -a
./  ../  .git/

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ../
bash: ../: Is a directory

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ cd ../

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop
$ ls
'Car Mechanic Simulator 2018.lnk'*   investing.ru.docx
'Dragon Age II.lnk'*                 repo/
'Pro Evolution Soccer 2019.lnk'*     repo-gui/
'Shadows Awakening.lnk'*             smart-lab.ru.docx
'Total Commander 64 bit.lnk'*        µTorrent.lnk*
'Victor Vran.lnk'*                  'Настройкки Pro Evolution Soccer 2019.lnk'*
 desktop.ini                        'фундаментальный анализ.rtf'

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop
$ cd repo-gui

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo-gui (main)
$ readme.md
bash: readme.md: command not found

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo-gui (main)
$ cat readme.md
repo-gui

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo-gui (main)
$ cd repo
bash: cd: repo: No such file or directory

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo-gui (main)
$ cd ../

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop
$ cd repo

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git remote add origin https://github.com/mbe-orley/repo-github.git

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git remote -v
origin  https://github.com/mbe-orley/repo-github.git (fetch)
origin  https://github.com/mbe-orley/repo-github.git (push)

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ touch readme.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git add readme.md
fatal: pathspec 'readme.md' did not match any files

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git add readme.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.txt


Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git commit
[master (root-commit) ecae50d] add readme.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master
nothing to commit, working tree clean

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ echo "edited" > readme.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git commit -am 'update readme.txt'
warning: LF will be replaced by CRLF in readme.txt.
The file will have its original line endings in your working directory
[master f19cf7a] update readme.txt
 1 file changed, 1 insertion(+)

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ mkdir images

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master
nothing to commit, working tree clean

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ touch images/ .gitkeep

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls
images/  readme.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls images

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls -a images
./  ../

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ touch images/.gitkeep

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls
images/  readme.txt

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls images

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ ls -a images
./  ../  .gitkeep

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitkeep
        images/

nothing added to commit but untracked files present (use "git add" to track)

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git add images

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$ git commit -m 'created images directory'
[master 26ee1f5] created images directory
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 images/.gitkeep

Asus@DESKTOP-4AEEPNB MINGW64 ~/Desktop/repo (master)
$

