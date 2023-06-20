# Križić-kružić igra u JupyterLab okolini

  Ova praksa baviti će se izgradnjom interaktivne igre
  [križić-kružić](https://en.wikipedia.org/wiki/Tic-tac-toe) unutar [JupyterLab
  notebooka](https://jupyter.org/) koja će se moći igrati na bilo kojem računalu
  koje sadrži sličnu programatsku okolinu za programski jezik Python.

  Križić-kružić igra trebala bi omogućiti igranje dva igrača na način da se
  naizmjeničnim klikanjem ispunjava [devet polja odijeljenih međusobno okomitim
  parovima paralelnih linija](https://www.thegamegal.com/2018/09/01/ultimate-tic-tac-toe/).
  Svakim klikom, u jedno od slobodnih polja trebalo bi se naizmjenice ucrtati križić ili
  kružić [u skladu s pravilima igre](https://en.wikipedia.org/wiki/Tic-tac-toe#Gameplay).

  Igra završava neriješeno u trenutku kada se ispune sva polja, osim kada se
  ispune uvjeti za pobjedu jednog igrača: tri uzastopna polja križića ili
  kružića. U slučaju neriješene igre iscrtana polja se brišu, dok se u slučaju
  pobjede dodaje jedan bod igraču koji je pobijedio. Broj bodova svakog igrača
  počinje s nulom i povećava se za jedan u slučaju pobjede. Trenutno bodnovno
  stanje mora biti prikazano pored polja na kojem se odvija igra.
  


# Zadaci

  1. Pripremiti okolinu za razvoj interaktivne igre korištenjem virtualnog okruženja [venv](https://docs.python.org/3/library/venv.html). Virtualnu okolinu imena `krizic_kruzic` treba napraviti u direktoriju u kojem
  će se razvijati sve naknadne skripte.
  1. Aktivirati virtualnu okolinu `krizic_kruzic`, instalirati knjižnice `jupyterlab`, `ipycanvas` i testirati
  njihovu instalaciju unutar jupyter notebooka imena `test.ipynb` (npr. `import ipycanvas`)
  1. Napisati funkcije koje korištenjem knjižnice `ipycanvas` i njegove funkcije
     [`Canvas`](https://ipycanvas.readthedocs.io/en/latest/basic_usage.html#) na
     grafu nacrtati:
      1. 3x3 križić kružić polje
      1. Crveni križić s proizvoljnom položajem unutar 3x3 polja
      1. Plavi kružić s proizvoljnim položajem unutar 3x3 polja
