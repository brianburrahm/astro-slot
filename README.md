# Astro Slot

A mobile-first celestial cascade game with a fixed 6×6 grid and twelve zodiac signs. Seven classical planetary rulers act as sign-specific wildcards.

## Play

- Spin to generate a board. Four or more orthogonally connected matching signs (at least two natural signs) clear and cascade.
- Ruling planets may substitute only for their traditionally ruled signs. Shared wilds are assigned once, prioritizing larger matches.
- A connected group of all three signs in an element can trigger a grand trine after ordinary matches are exhausted, once per spin.
- A Sun in a Leo match clears neighboring tiles. Three Moons on the initial board award five free spins. Five distinct rulers on the initial board earn a Zodiac Wheel turn. Every four spins also earn a turn.
- Twenty regular spins per session, plus earned free spins. Points are purely virtual. No purchases, real money, prizes or cash redemption.

## Planetary powers

The Zodiac Wheel awards one of six powers, bonus points, or free spins. Earned power charges can be banked and used between spins. Select a power and then a tile, or cancel without spending a charge. Normal tile taps open the astrology information card.

- Mercury: swap two adjacent, unsealed tiles.
- Saturn: anchor one tile through the next spin; it can contribute to matches but cannot be cleared or moved while sealed.
- Mars: clear a tile and resolve cascades.
- Venus: bring the nearest matching zodiac sign into a neighboring square.
- Jupiter: double the next scoring alignment.
- Moon: choose any zodiac sign to replace a tile.

Power charges and wheel turns reset with a new session or page reload.

## Publish

In the repository's Settings → Pages, select Deploy from a branch, main, /(root), then Save. The application is self-contained in index.html and does not require a build process, server, external assets or analytics.

Game mechanics are inspired by traditional astrology rather than literal astrological predictions.
