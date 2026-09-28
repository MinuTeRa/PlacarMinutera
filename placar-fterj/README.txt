V38 UNIFICADO GITHUB PAGES - SEM ?= 

COMO USAR NO GITHUB PAGES:
1. Na pasta placar-fterj/ do seu repo, coloque:
   - index.html (este arquivo unificado)
   - 404.html (copia identica do index.html)

2. GitHub Pages quando recebe /tv1, /resultado/C etc que nao existe como arquivo,
   serve o 404.html que tem o mesmo roteador e abre a view correta.

LINKS LIMPOS SEM ?= :
/placar-fterj/ -> INDEX lancamento (ordem = V36.6, 078 em cima)
/placar-fterj/tv -> TV padrao com desempate X>10>9>8...
/placar-fterj/tv1 -> TV1
/placar-fterj/tv2 -> TV2
/placar-fterj/resultado -> Resultado sem anuncio
/placar-fterj/resultado/C -> Resultado filtrado prova C (sem ?prova=C)
/placar-fterj/celular -> Celular
/placar-fterj/controle -> Controle completo (FULL, RODAPE, RESULTADO, PROVA, TV, LINKS)

Nao precisa de ?tv=tv1 nem ?prova=C mais.

O INDEX continua lendo igual V36.6 (ultimo em cima).
TV/RESULTADO/CELULAR com desempate completo X>10>9>8>7>6>5>4...
