# Auditorieopgaver i Lektion 10
Live coding foregår i [src/live.c](src/live.c) og det færdige kode ligner det i [src/car.c](src/car.c).

---
## Auditorieopgave A
Du kan skrive din kode i filen [src/planet.c](src/planet.c).

> Lav en struct `plаnet` med følgende felter:
> - `navn`
> - `volumen` i km³ (som en `double`)
> - `masse` i kg (som en `double`)
>
> Lav en funktion som givet en planet returnerer dens massefylde.
>
> Prøv funktionen af på to konkrete værdier (Jorden og Mars f.eks.)

---
## Auditorieopgave B: Alvor
Fortsæt i filen [src/planet.c](src/planet.c).

> Udvid planet-typen sådan at den har følgende felter:
> - `navn`
> - `radius`
> - `volumen`
> - `masse`
>
> Lav en indlæsnings-funktion der beder om `navn`, `radius` og `masse`.
>
> Den skal ikke bede om `volumen`.
>
> I stedet skal den udregne `volumen` og indsætte resultatet på `volumen` feltet.
>
> Udskriv til sidst planeten.
>
> (Hint: $V = \frac{4}{3} \pi r^3)$
>
> ---
>
> (Bonus: Lad brugeren bestemme et antal planeter der skal indtastes, udskriv dem alle.)
