### e. recurrance relation
rakningarvensl fyrir runu **$\{a_n\}$** er jafna sem skilgreinir **$\{a_n\}$** sem fall af einum eða fleiri fyrri liðum rununnar, þ.e. frá og með **$a_0$** upp að og með **$a_{n-1}$** fyrir öll stök sem eru stærri en **$n_0$**, þar sem **$n_0$** er jákvæð heiltala 

# dæmi:
látum $\{a_n\}$ vera runu sem uppfyllir $\{a_n\}=a_{n-1}+3$ fyrir $n=1,2,3,...$ og látum $a_0=2$ þá eru:
> $a_1=a_0+3=2+3=5$
> $a_2=a_1+3=5+3=8$
> $a_3=a_2+3=8+3=11$

ein leið til þess að finna lausn á rakningarvenslinu væri með því að vinna sig afturábak og finna mynstur, það kallast **ítrun**(*e. iteration*)
$a_n$:
> $=a_{n-1}+3$
> $=(a_{n-2}+3)+3$
> $=(a_{n-3}+2*3$
> ...
> $=a_2+3(n-2)$
> $=(a_1+3)+3(n-2)$
> $=2+3(n-1)$

