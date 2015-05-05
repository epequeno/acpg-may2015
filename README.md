Presentation to Alamo City Python Group

Thursday May 7, 2015

https://slides.com/estevanpequeno/acpg-may2015

---

Install stats:
before install (with only virtualenv):
```
(.acpg)~/c/acpg-may2015 (master) $ du -sh
11M
```

after install using "pip --no-cache-dir install -r requirements.txt"
```
(.acpg)~/c/acpg-may2015 (master) $ du -sh
165M
```

after install using "pip --no-cache-dir install -r requirements-extra.txt"
```
(.acpg)~/c/acpg-may2015 (master) $ du -sh
268M
```

time to install requirements.txt: 
```
439.18user 15.27system 7:35.61elapsed 99%CPU
```

***Note***: installing extras (like seaborn) will also require a fortran compiler.

time to install requirements-extra.txt: 
```
917.67user 33.22system 16:17.28elapsed 97%CPU
```
