% Versionsverwaltung mit Git 
% Max Nagy 
% 8. Juli 2019 

# Warum git?

```
objc[80911]: Class JavaLaunchHelper is implemented in both /Library/Java/JavaVirtualMachines/jdk1.8.0_111.jdk/Contents/Home/bin/java (0x10a6324c0) and /Library/Java/JavaVirtualMachines/jdk1.8.0_111.jdk/Contents/Home/jre/lib/libinstrument.dylib (0x10be5c4e0). One of the two will be used. Which one is undefined.
Exception in thread "main" java.io.FileNotFoundException: /global/home/users/giladk/Datasets/heart.arff (No such file or directory)
	at java.io.FileInputStream.open0(Native Method)
	at java.io.FileInputStream.open(FileInputStream.java:195)
	at java.io.FileInputStream.<init>(FileInputStream.java:138)
	at java.io.FileInputStream.<init>(FileInputStream.java:93)
	at java.io.FileReader.<init>(FileReader.java:58)
	at explorekit.Program.main(Program.java:37)

Process finished with exit code 1
```

# Warum git?

```
This is pdfTeX, Version 3.14159265-2.6-1.40.17 (TeX Live 2016) (preloaded format=pdflatex)
```
. . . 
```
 restricted \write18 enabled.
entering extended mode
(./test.latex
LaTeX2e <2016/03/31>
Babel <3.9r> and hyphenation patterns for 83 language(s) loaded.
! Undefined control sequence.
l.1 \hypertarget
                {gliederung}{%
?

! LaTeX Error: Missing \begin{document}.

See the LaTeX manual or LaTeX Companion for explanation.
Type  H <return>  for immediate help.
 ...
```

# Warum git?

* "Snapshots" wichtiger Zwischenergebnisse - _commits_
* Backups - _remotes_
* Fehler finden oder rückgängig machen - _checkout_, _diff_
* strukturierte Kollaboration  

# git setup

* Basic Installation:
	* https://git-scm.com/downloads
	* Ubuntu: `sudo apt-get install git`
	* mac: `brew install git`
* Graphische Clients: 
	* https://desktop.github.com (Windows/Mac)
	* https://www.gitkraken.com/ (Windows/Mac/Linux)
* Semigraphischer Client:
	* https://tortoisegit.org (Windows)
* Hosting
	* **https://github.com**
	* https://gitlab.com

# git setup

```bash
cd
ssh-keygen
cat .ssh/id_rsa.pub
```

# git basics

```bash
git init

git status
git add # bzw. git reset
git commit -m "Did some stuff"

git log
git diff

git pull
git push

git branch
git checkout
```

# Fragen

Jannic:Janick

Dennis: Wie kommen die "Rasen betreten verboten" Schilder in die Mitte des Rasens?

Simon:

# Fragen II

Basti:Jetzt mal im ernst, was mach ich hier?

Consti: 
Warum stinkts Dennis so?

Max: 
 * haben Sie überhaupt Abitur?

Carlos:

