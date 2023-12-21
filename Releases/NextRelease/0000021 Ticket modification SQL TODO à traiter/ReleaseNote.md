# RELEASE NOTE

## 00000021 Modification SQL TODO à passer en "A traiter"
- passer les TODO en à traiter
update todos set IsProcessed=0 where IsProcessed=1;