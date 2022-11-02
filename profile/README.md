# Czechitas-Python GitHub organizace

Obsahuje repozitáře s texty k Python kurzům na [kodim.cz](https://www.kodim.cz).


## Návod pro přispěvovatele bez oprávnění k zápisu

Pokud se vám něco v textu nezdá, stačí nejprve otevřít issue k diskuzi. Není nutné hned posílat PR.

### Obecný postup přispívání do open source

_Pozn.: Jedná se o subjektivní popis práce s GitHubem. Není to to jediná možnost. Možná jsou i jednodušší cesty._

* Forkněte si příslušené _repo_
* Naklonujte si váš _fork_
* Přidejte si do vašeho _clonu_ další _remote_ (např. jej pojmenujte _upstream_)
```
git remote add upstream https://github.com/Czechitas-Python/uvod-do-progr-1.git
```
* Pravidelně si stahujte změny z hlavního repa pomocí `git fetch upstream`
* Změny si _rebasujte_ do svého _main_ např. `git rebase upstream/main` a `git push`.
* Pro každý _fix_ si vytvořte vhodně pojmenovanou větev ve svém _forku_
* Pošlete _PR_ z této větve do _main_ hlavního repa
    * Možno využívat označení _Draft_, pokud je změna ještě ve vývoji


## Pravidla pro vlastníky a členy se zápisem do repozitářů

* Děláme vždy PR, pokud to není urgentní fix vážně rozbitého textu na kodim.cz
* PR vždy z vhodně pojmenované větve (např. název začíná jménem majitele)
* Kdo má právo zápisu do repa, může vytvářet větve přímo v repu a nemusí pracovat se svým _forkem_
* Po zamergování PR vždy smažeme původní větev ze společného repa
* PR musí mít vždy alespoň jedno review
* PR akceptuje autor (pokud má právo zápisu), ne reviewer, popř. garant kurzu
* PR se akceptuje pomocí _Squash commits and rebase_ pokud má víc commitů (další commity fixovaly ten PR), jeden commit se zamergovává _Rebase and merge_, merge commity jsou vypnuty


## Dashboard PR a issues

Obsahuje přehlednou stránku se všemi otevřenými PR a issues pro repozitáře z Python kurzů: https://czechitas-python.github.io/

## Czechitas-Python owners

[@podlomar](https://github.com/podlomar), [@pesikj](https://github.com/pesikj), [@lutydlitatova](https://github.com/lutydlitatova), [@ZelenyMartin](https://github.com/ZelenyMartin)
