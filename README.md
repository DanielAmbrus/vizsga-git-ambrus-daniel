
Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git init
Initialized empty Git repository in C:/Users/Daniel/Desktop/git-vizsga0104/.git/

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        README.md
        app.js
        images/
        index.html
        music/
        style.css

nothing added to commit but untracked files present (use "git add" to track)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git commit -m "klonozott és létrehozott fájlok commitolása"
[main (root-commit) 2e5f312] klonozott és létrehozott fájlok commitolása
 13 files changed, 277 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 images/hey.jpg
 create mode 100644 images/river.jpg
 create mode 100644 images/summer.jpg
 create mode 100644 images/ukulele.jpg
 create mode 100644 index.html
 create mode 100644 music/hey.mp3
 create mode 100644 music/river.mp3
 create mode 100644 music/summer.mp3
 create mode 100644 music/ukulele.mp3
 create mode 100644 style.css

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git branch console

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git checkout console
Switched to branch 'console'
M       .gitignore

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git checkout main
Switched to branch 'main'
M       .gitignore

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git commit -m "branch létrehozása és -gitignore elmentése"
[main 656363b] branch létrehozása és -gitignore elmentése
 1 file changed, 4 insertions(+)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$ git checkout console
Switched to branch 'console'

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git commit -m "üzenet hozzaadása console-hoz"
[console e441613] üzenet hozzaadása console-hoz
 1 file changed, 4 insertions(+)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git status
On branch console
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git status
On branch console
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   style.css


Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git commit -m "oldal háttérszínének módosítása css-ben"
[console ba3746d] oldal háttérszínének módosítása css-ben
 1 file changed, 1 insertion(+), 1 deletion(-)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (console)
$ git checkout main
Switched to branch 'main'

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/git-vizsga0104 (main)
$