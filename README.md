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
## lokális változások szinkronizálása a távoli repóba
- git push
## Távoli repó másolása a lokális repóba
- git clone "távoli repó URL címe"