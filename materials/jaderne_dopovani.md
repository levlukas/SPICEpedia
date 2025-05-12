# Dopování polovodičů jadernými reakcemi

## Úvod
Běžně se využívají metody **difúze** a **iontové implantace**, kdy se zabudovává cizí hmota do samotného polovodiče *(pozn. rozdíl v koncentrácích příměsi a Si je přesto v řádech $10^n$)*.

- [ ] TODO: dopsat koncentrace

Během dopování jadernými reakcemi dochází k transmutaci (umělé přeměně atomových jader) za vzniku dopovacích prvků.

## Si a jaderné procesy
V přírodním křemíku jsou obsaženy celkem 3 izotopy:
$$_{14}Si^{28} - 92,21\text{ \%, }_{14}Si^{29} - 4,70\text{ \%, }_{14}Si^{30} - 3,09\text{ \%}$$

Existuje také radioaktivní isotop křemíku degradující na fosfor:
$$_{14}^*Si^{31} \rightarrow |{\tau=10^4 s}| \rightarrow _{15}P^{31} + _{-1}e^0$$

## Realizace transmutace
1. Bombard vysokoenergetických nabitých částic
2. Fotojadernými reakcemi ($\gamma$)
3. Bombard pomalými (tepelnými) neutronynebo 

### Bombard vysokoenergetických nabitých částic
Při bombardu helionem mohou vznikat následující reakce

- [ ] TODO: nechat chata přepsat do latexu

![helion.png](:/ed311846d3144cf5bce08430ae20bff2)

## Fotojadernými reakcemi ($\gamma$)

![gamma.png](:/70fdf84c5af24aac86cb7be7273eab74)

### Bombard tepelnými neutrony
- [ ] TODO: proč pomalé lepší?
Pro kvantifikaci pravděpodobnosti srážky neutronu s jádrem se uvažuje jak geometrický průřez jádra, tak jeho tzv. účinný průřez $\sigma$, jež charakterizuje průřez objemu zaručující pravděpodobnou jadernou reakci.

- [ ] TODO: obrázek

Jako zdroj tepelných neutronů se používá jaderný reaktor:

- [ ] TODO: obrázek konstrukce

Rovnice bombardování: 
![neutron.png](:/df835f03335a4d23b987eeb6529dff3e)

Při dlouhodobém ozařování za snížení vnitřního odporu pod $0,05\text{ }\Omega\text{m}$ existuje nebezpečí vzniku radioaktivního fosforu, jež degraduje na síru $_{16}S^{32}$.

## Výstupní koncentrace
Protože pro průchod záření látkou platí exponenciální pokles intenzity záření v závislosti na hloubce, projeví se nedokonalosti.

$$I(x) = I_0 \exp{\left[ -\alpha(\lambda)\cdot x \right]}$$

Pro koncentraci donorů v křemíku navíc platí následující vztah:
$$N_D = \frac{1}{q\rho_1\mu}-\frac{1}{q\rho_0\mu_o} = p_i\cdot N_{Si}\cdot\sigma_n\cdot\varphi \cdot t,$$
kde $\mu$ jsou pohyblivosti, $\rho$ jsou vnitřní odpory, $p_i$ je relativní zastoupení izotopu křemíku, $N_{Si}$ je koncentrace atomů křemíku, $\varphi$ je plošná hustota toku částic a $t$ je čas expozice.

- [ ] TODO: vynést závislosti, popsat blíže dalšími modely, srovnání koncentrací s jinými metodami a funkce $\text{koncentrace}(x)$

## Masky pro ozařování
Různé materiály mají vlastní závislosti pro absorbční koeficient $\alpha(\lambda)$. Pro tvorbu masek se používá např. $Cd$ jako dobrý absorber a $Al$ jako propustný materiál.

## Využití
V silnoproudé elektrotechnice je nutná homogenita v dopování křemíkových objemů. Takto dopované materiály se mohou používat pro výrobu vysokovýkonných diod (až 3 kA).

- [ ] TODO: obrázek

# Zdroje
- [ ] dodělat

KAZELLE JIŘÍ, *Název textu*