# Branchit

## Komentoja

### Branch

- Branchin luominen
  - `git branch <nimi>`
  - esimerkiksi `git branch feat-1`
- Branchiin vaihtaminen
  - `git checkout <nimi>`
  - esimerkiksi `git checkout feat-1`
- Luo uuden branchin ja vaihtaa siihen
  - `git checkout -b <nimi>`
  - esimerkiksi `git checkout -b feat-2`
- Branchien listaus
  - `git branch -a`
- Kahden branchin yhdistäminen
  - `git merge <nimi>`
  - esimerkiksi `git merge feat-2`, yhdistää `feat-2`-branchin siihen branchiin mikä on aktiivisena kun ajat komennon

### Log

- Login piirtäminen graafina
  - `git log --oneline --graph`

### Commit

- `git commit -am 'viesti'`
  - `git add`aa kaikki tiedostot (`-a`) ja tekee commitin
  - Käytä `-a`-lippua varoen! Vain silloin kun tiedät varmasti, että committiin ei mene mukaan ei-haluttuja muutoksia.
