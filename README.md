Presentation to Alamo City Python Group

Thursday May 7, 2015

https://slides.com/estevanpequeno/acpg-may2015

Status: finalized

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
250M
```

time to install requirements.txt: 
```
439.18user 15.27system 7:35.61elapsed 99%CPU
```

***Note***: Installing extras (Seaborn, ggplot, bokeh) will also require
installing system packages (lapack/blas, fortran compiler).

time to install requirements-extra.txt: 
```
967.12user 38.75system 17:29.86elapsed 95%CPU
```
