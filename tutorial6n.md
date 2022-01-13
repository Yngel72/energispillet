### @activities true

# Grensekontroll - lag en usynlig grense og sett opp en grensevakt!
## Introduksjon
### Introduksjon @unplugged
Nå skal vi lage en usynlig grense som bare kan krysses ved en kontrollstasjon. Da blir det vanskeligere for rivaler å stjele ressurser fra ditt område, men kanskje det gjør spillet vanskeligere for deg også?

### Steg 1
Først må vi sette opp en grensevakt. Grensevakten må være en egen ``||Scene.tile||``. Klikk på kartikonet i ``||Scene.set tilemap to||``, finn en ``||Scene.tile||`` du synes passer som grensevakt og plasser den der de to øyene møtes.

### Steg 2
Klikk på kartikonet i ``||Scene.set tilemap to||``-blokken på nytt. Klikk på vegg-ikonet under det lille bildet av kartet på venstre side av skjermen. "Draw walls" kommer opp under ikonet når du peker på det.

### Steg 3
I ditt eget spill kan du gjenta Steg 2 for alle ``||Sprites.on sprite of kind player overlaps otherSprite of kind [EnergyKind]||``-blokker som representerer fossile energikilder.Fornybare energikilder kan stå som de er, ettersom de ikke påvirker miljøet i like stor grad.

### Steg 4
Hva skjer når planeten går tom for liv? Det sier seg kanskje selv, men du må bruke en ``||Info.on life zero||``-blokk fra ``||Info.Info||``-menyen for at noe skal skje. Du kan for eksempel sette inn lyd fra ``||Music.Music||``-menyen, animere skjermen med blokker fra ``||Scene.Scene||``-menyen, eller kanskje bare sette inn en ``||Game.game over||``-blokk fra ``||Game.Game||``-menyen? (Advarsel: ``||Game.game over||``-blokken vil gjøre du mister effekten av alle andre blokker inni ``||Info.on life zero||``-blokken.)

### Steg 5
Det var alt om miljøpåvirkning.
Her er en ekstra liten utfordring:
Noen handlinger har positiv effekt på miljøet. Hva med å tilføye noen få sprites som gir liv til planeten når du plukker dem opp? Kanskje plastsøppel i havet? Hvilke blokker kan du bruke for å få til dette?

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
