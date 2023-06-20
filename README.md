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
  počinje s nulom, i povećava se za jedan u slučaju pobjede.

# Zadaci

  1. Pripremiti okolinu korištenjem virtualnih okruženja [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html). Predložene knjižnice za izradu interaktivne igre su `ipywidget` i `ipycanvas`, no mogu biti proizvoljno odabrane ako omogućuju traženu funkcionalnost (ili izradu interaktivne igre u Jupyter notebooku)
  1. 
