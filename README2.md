Vi har til opgave at gøre en hjemmeside interaktiv samt anvende flere ting fra undervisningen, blandt andet layout-patterns og container queries.

Opgaven har været spændende, men også udfordrende, da vi ikke har haft så lang tid til at arbejde med siden. En af de største udfordringer har været at omdanne siden fra computer- til mobilversion, da mange af vores section-grids pludselig ikke reagerede, selv efter at vi slettede CSSen, ændrede layoutet sig ikke.

Bortset fra det har vi løst andre udfordringer, blandt andet de grønne blokke bag billederne. Dem er vi meget glade for, da de giver siden mere liv.

En kodestump, vi især synes godt om, er nesting af media queries i stedet for at have dem separat. Det gør det lettere at holde styr på CSSen.

Vi har anvendt flere defensive CSS-teknikker, blandt andet :has()selectoren på nogle elementer, hvilket har været nyttigt, da vi ikke behøvede at sætte en ekstra klasse på elementerne.

Vi har også brugt progressive enhancement med @supports / @supports not, som har hjulpet os med at kode funktionalitet, der kun aktiveres, hvis browseren understøtter bestemte CSS-egenskaber.

Vores CSS er global, når det smides i et layout, som importeres på hver side. På siderne importeres også komponenter, og for at stylingen kun skal gælde komponenterne, har vi skrevet CSS specifikt i komponenterne.