# VCF Tycoon

A browser game set in a 3D model of the VCF Montréal 2026 show hall (Room D 121, Nov 7-8),
plus a plain walk-through of the hall, three prequels and two small games.

## The pages

| Page | Link | What it is |
|---|---|---|
| **The game** | https://cmolson.github.io/vcf-mtl-tycoon/ | VCF Tycoon: play a weekend at the show, or walk around the hall. |
| **The hall walk-through** | https://cmolson.github.io/vcf-mtl-tycoon/walkthrough.html | Just the hall: the V22 floor plan in 3D, booth names and cards, the speakers' corner, a guided tour. No game. French / English (add `?lang=fr` or `?lang=en`). Made to be embedded on the show's website. |
| **COPY PROTECTED** | https://cmolson.github.io/vcf-mtl-tycoon/copyprotected.html | Crack the hall, booth by booth: quick microgames about 1980s copy protection (code wheels, manual lookups, key disks, dongles, lens decoders, colour charts). Cracked booths show your initials; finish an island for a cracktro. French / English. |
| **Boothle** | https://cmolson.github.io/vcf-mtl-tycoon/boothle.html | A daily puzzle: one close-up from the hall, six guesses on the floor plan, a result to share. A new one every day until the show. French / English. |
| **The drive** | https://cmolson.github.io/vcf-mtl-tycoon/roadtrip.html | Prequel: pack the car in Ottawa, drive the 417 and the A-30 to Saint-Lambert. |
| **TDK's flight** | https://cmolson.github.io/vcf-mtl-tycoon/flight.html | Prequel: CF-UKN, a Beaver on floats, from Lynn Lake to the St. Lawrence with a load of mainframe parts. |
| **Nick's crossing** | https://cmolson.github.io/vcf-mtl-tycoon/nick.html | Prequel: Nick's walk across Riverside Drive. |

## The game

Play a weekend at the show, Friday load-in to Sunday teardown, as:

- **Land of the Portables**: vintage luggables and laptops, the guest book, Dial-a-Museum.
- **Griefenbunker LAN**: keep the LAN party's seats full and the players happy.
- **Nick, the showrunner**: the whole hall: check-in, power, badges, payments, volunteers.
- **Clint, the retro-tech video maker**: a line of fans at the guest table, forty booths to film.

Or just walk around the hall. There's also an 8-minute show-floor demo. French / English.

The game is the one `index.html` (three.js and everything else embedded; it works offline
too). Controls: WASD / arrows to walk, drag to look (or F for full screen with mouse look),
E or click to use things.

**Prequels.** How everyone got to the show, each a short game of its own: [the drive](roadtrip.html),
[TDK's flight](flight.html) and [Nick's walk across Riverside Drive](nick.html). In the game, they are
behind the "Prequel" paper tape on the pick card. They are in English for now.

## COPY PROTECTED

Walk to the booth whose screen is flashing and crack it: five microgames of about ten seconds
each, three lives. Your initials stay on its screen. Crack four booths for your first cracktro,
and a whole island for another. Share your card; a friend who opens it sees your initials in the
greetz. One thumb on a phone, or the keyboard. The schemes are the real ones from the period;
the art, names and music are original.

## Boothle

A new close-up from the hall every day, the same for everyone. Tap the booth you think it is on
the map; each miss says hot, warm or cold with an arrow, and the picture widens a little. Six
guesses. Share the result as a line of squares. `?practice` plays random ones.

## The walk-through

`walkthrough.html` is small (about 240 KB) and loads three.js from a CDN. It opens on a
fly-over of the whole hall; Walk, 3rd person and Fly around are in its menu, along with
booth names, table skirts (coloured by booth type), the crowd and the go-to places.
The layout is preliminary: booths may still move before the show.

**Found a bug?** The version is in the corner of the game's screen (click it to copy), and in
the page source of every page. Please include it.

**Privacy.** Your saves, options, scores and trophies stay in your browser (localStorage);
nothing about you is sent anywhere. The game fetches its fonts from Google Fonts; the
walk-through, the prequels, COPY PROTECTED and Boothle load three.js from a CDN.
/ **Confidentialité.** Tes parties, tes options, tes scores et tes trophées restent dans ton
navigateur ; rien sur toi n'est envoyé. Le jeu charge ses polices depuis Google Fonts ; la
visite, les préquelles, COPY PROTECTED et Boothle chargent three.js depuis un CDN.

A fan project for VCF Montréal. Booth names are from the show's public floor plan. The
game's characters are fictional; the famous computer people who turn up are fans in costume
("lookalikes"), and CelGen Studios appears as a guest under the channel's own name. Music:
Scott Joplin rags (public domain), MIDI from the Mutopia Project, played on a synthesised
piano; COPY PROTECTED's chiptune is original. 3D engine: three.js (MIT).

**License:** MIT for this project's own code and content (see `LICENSE`). Third-party parts and names: see `THIRD-PARTY-NOTICES.md`.
