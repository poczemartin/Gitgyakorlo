# Verziókezelés alapjai
## git letöltése
- [git for windows]https://gitforwindows.org/
## konfigurációs parancsok
- git config --global user.name
- user helyett email
- credential.helper wincred
  ## repository létrehozása
- git init
## állomány hozzáadása a stage-hez
- git add állomány neve
- git add . (összes állomány és mappa)
## állapotfelvétel )commit készítése 
- git commit -m "commit message"
 ## Git állapot
 - git status
 - git log
## lokális változások feltöltése a távoli repóba
- git push
## Távoli repó másolása a lokális repóba
- git clone "távoli repó URL címe"
## Ágak (branches) kezelése
> Lokális ágak listázása
- git  branch
> Lokális és távoli ágak listázása
- git branch -av
> ág létrehozása
- git branch újágneve
- git checkout -b újágneve
> váltás egy másik ágra
- git checkout ágnév
> változások átvezetése (merge)
- git checkout ágahovakerülnekaváltozások
- git merge ahonnanáthozzukaváltozásokat
# Távoli repó változásainak letöltése a lokális gépre
- git fetch origin