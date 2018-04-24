Copyright: Tero karvinen 2018

## Pohja
### Asenna Git ja luo uusi kansio projektille.
 
#### Komennot:
	git init

#### Luo reposition.
	git add .

#### Valmistelee kaikki kansion tiedostot siirtoa varten.
	git commit

#### Siirtää tiedostot, kommentoi.
	git reset --hard

#### Palaa edelliseen commitiin.
	git blame tiedosto

#### Näyttää, kuka on kirjoittanut rivit.
	git diff id id2

#### Näyttää muutokset kahden commitin välillä.
	git log

#### Näyttää tehdyt commitit ja tekijät sekä aikaleimat.
	git log -p

#### Näyttää kaikkien tehtyjen commitien sisällöt.
	git add . && git commit; git pull && git push

#### Tallenna salasana ~ajaksi:
	git config --global credential.helper "cache --timeout=3600"

