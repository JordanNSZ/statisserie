# Documentation du tuto statisserie.

```bash
git init
git config --global init.defaultBranch main
git config user.name JordanNSZ
git config user.email "jordan.nagadzina.sanchez@gmail.com"
```

## Comparaison de deux proportions.

### Test Exact de Fisher.

La statistique du test exact de Fisher est, pour une configuration donnée : 

p = (n1!n2!N!) / (a!b!c!d!)

### Test du Chi-2.

La statistique du test du Chi-2 compare la situation observée à une situation d'indépendance - i.e. situation théorique. 

p = \sum_{i \in k} (Eo_i - Et_i) / Et_i

### Lequel choisir ?

Dans la mesure où le test du Chi-2 est une estimation approximative de la probabilité et, que le test de Fisher est une estimation exacte de cette probabilité, il est préférable d'employer le test exact de Fisher ; combien même il existe un test du Chi-2 avec correction de Yates. 