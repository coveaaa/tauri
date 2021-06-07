# Tauri
Mon avancement dans le projet Tauritech !

Nous sommes le Lundi 7 juin 2021, Tauritech est en "beta" et voici notre avancement :

Présentation de mon projet : 
Mon objectif étant de fournir des proxies pour absolument tout et tout le monde, il va de soi que nous devons avoir de quoi faire au niveau des IP pool.
Auparavant via assproxies, j'utilisais un bref script reconstitué par moi-même pour faire des proxies via AWS et Google, j'avais à ma disposition plus ou moins 3 pools de 2k IP chez AWS et 1 pool de 1k IP chez Google. J'avais à cet époque-là une vision bien différente d'aujourd'hui, les providers étaient des voleurs qui profitaient de la communauté en faisant le moins d'effort possible. De par l'utilisation de "wholesaler", ils n'agissaient qu'en tant que reseller, ce qui reste partiellement vrai. Aujourd'hui je comprends que le sujet est plus complexe que dit précédemment. Pour de plus amples explications, nous nous devons de présenter l'importance du type de proxies, quels sont les types de proxies, comment fonctionnent t'ils, quels sont les caractéristiques et l'enjeux de ces caractéristiques.
Il existe aujourd’hui en gros trois types de proxies, basé sur l’origine de l’adresse IP et non pas le protocole utilisé ou le système comme nous pourrions voir ailleurs dans l’utilisation première des proxys.
Ici nous pouvons séparer dans 3 grosses catégories :
-	Datacenter (DC) proxies
-	ISP
-	Residentials
Un DC est un proxy avec comme base une IPV4 fournis par une entreprise particulière host dans un datacenter (d’où le nom).
Un ISP est un proxy avec comme base une ipv4 founis par un télécom tel que Orange, SFR, etc… host dans un datacenter. ISP venant de l’anglais ISP provider = télécom.
Un Resi (Residential) est un proxy avec comme base une ipv4 fournis par un télécom et host chez un particulier.
Les caractéristiques générales sont les suivantes :
Un DC est le type de proxies le plus rapide mais le moins qualitatif, de par l’adresse Ipv4 provenant d’une entreprise, les DC sont souvent flag par les retailers généraux.
Un ISP a pour principe d’avoir une vitesse de ping égale au DC mais il n’en est pas le cas mais nous y reviendrons plus tard. Et de par l’adresse Ipv4 provenant d’un télécom, les ISP ne sont que très peu flag par les retailers.
Un rési quand a lui est donné comme lent mais avec les avantages d’un IPV4 d’un ISP.






Notre objectif : Faire des proxies
