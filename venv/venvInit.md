
# Venv je orodje za virtualno okolje

## Inicialnizacija
Inicializacija v mapi projekta (.venv je mapa v katero bodo shranjenih datoreke virtulnega okolja)
```bash
python3 -m venv .venv
```
## Aktiviranje okolja
Ustvari se skrit direktorij .venv. 
Navigiraj v .venv
```bash
cd .venv/
```
Aktiviraj okolje 
```bash
source bin/activate
```
Zaj lahko dodajaš knjižnice v virtualno okolje

## Deaktiviranje okolja
V okolju zaženemo ukaz deactivate
```bash
deactivate
```

## Requirements
Pri deljenju kode je smiselno dodati seznam knjižnic, ki smo jih uporabili. Seznam requirements.txt ustvarimo tako, da v AKTIVIRANEM okolju poženemo naslednji ukaz:
```bash
pip3 freeze > requirements.txt
```

## Gitignore
Direktorij ```.venv/``` je smiselno dodati v datoteko .gitignore.

