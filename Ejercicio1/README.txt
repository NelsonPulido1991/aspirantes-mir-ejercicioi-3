nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop (master)
$ pwd
/c/Users/nelso/OneDrive/Desktop
nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop (master)
$ git -v
git version 2.40.1.windows.1
nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop (master)
$ mkdir Ejercicios

nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop (master)
$ cd Ejercicios

nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios (master)
$ git config --global user.name "Nelson Pulido"

nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios (master)
$ git config --global user.email "NelsonPulido19@gmail.com"
nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=NelsonPulido19@gmail.com
user.name=Nelson Pulido
user.emal=nelsonpulido19@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios (master)
$ git init
Initialized empty Git repository in C:/Users/nelso/OneDrive/Desktop/Ejercicios/.git/
nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios/Ejercicio1 (master)
$ LS
README.txt
nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios/Ejercicio1 (master)
$ git add README.txt

nelso@LAPTOP-VAARF69E MINGW64 ~/OneDrive/Desktop/Ejercicios/Ejercicio1 (master)
$ git commit -m "Version Inicial"
[master (root-commit) 3485d93] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Ejercicio1/README.txt
