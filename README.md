# VCF Tycoon

A browser game set in a 3D model of the VCF Montréal 2026 show hall (Room D 121, Nov 7-8),
plus a plain walk-through of the hall.

## The two pages

| Page | Link | What it is |
|---|---|---|
| **The game** | https://cmolson.github.io/vcf-mtl-tycoon/ | VCF Tycoon: play a weekend at the show, or walk around the hall. |
| **The hall walk-through** | https://cmolson.github.io/vcf-mtl-tycoon/walkthrough.html | Just the hall: the V22 floor plan in 3D, booth names and cards, the speakers' corner, a guided tour. No game. French / English (add `?lang=fr` or `?lang=en`). Made to be embedded on the show's website. |

## The game

Play a weekend at the show, Friday load-in to Sunday teardown, as:

- **Land of the Portables**: vintage luggables and laptops, the guest book, Dial-a-Museum.
- **Griefenbunker LAN**: keep the LAN party's seats full and the players happy.
- **Nick, the showrunner**: the whole hall: check-in, power, badges, payments, volunteers.
- **Clint, the retro-tech video maker**: a line of fans at the guest table, forty booths to film.

Or just walk around the hall. There's also an 8-minute show-floor demo.

The game is the one `index.html` (three.js and everything else embedded; it works offline
too). Controls: WASD / arrows to walk, drag to look (or F for full screen with mouse look),
E or click to use things.

## The walk-through

`walkthrough.html` is small (about 240 KB) and loads three.js from a CDN. It opens on a
fly-over of the whole hall; Walk, 3rd person and Fly around are in its menu, along with
booth names, table skirts (coloured by booth type), the crowd and the go-to places.
The layout is preliminary: booths may still move before the show.

**Found a bug?** The version is in the corner of the game's screen (click it to copy), and in
the page source of both pages. Please include it.

A fan project for VCF Montréal. Booth names are from the show's public floor plan. The
game's characters are fictional; the famous computer people who turn up are fans in costume
("lookalikes"), and CelGen Studios appears as a guest under the channel's own name. Music:
Scott Joplin rags (public domain), MIDI from the Mutopia Project, played on a synthesised
piano. 3D engine: three.js (MIT).
