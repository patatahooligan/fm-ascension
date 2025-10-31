# Ascension

Ascension is a minimal Yu-Gi-Oh! Forbidden Memories mod that makes all
cards available and significantly reduces the grinding required to beat
the game. Beyond these goals, Ascension tries to stay as true to the
spirit of the original game as possible.

Ascension is currently incomplete. The current version of the mod might
not 100% achieve the stated goals.

## Building

This mod is written for use with [fmde][1]. See fmde's documentation for
setting it up and using it. To apply the mod run

```bash
fmde apply \
    path/to/rom.bin \
    path/to/ascension-repo/ \
    path/to/save/mod.bin
```

The ROM file is *not* included here. It is proprietary software that
would be illegal to distribute in many countries. You have to figure out
how to obtain it legally based on where you live.

[1]: https://github.com/patatahooligan/fmde

## Changes and rationale

- All 722 cards are collectible. This is a widely desired feature with
  no downside so there's nothing to explain.
- All cards, even the strongest ones, have at least one duelist that
  drops them at a reasonable rate. As a baseline, every card should be
  obtainable with at least 1/64 odds from at least one duelist. The goal
  is to allow consistently building strong enough decks to beat the
  game. Getting a full collection and/or a full playset (3 copies) of
  every rare card can still take hundreds/thousands of duels on average.
  For magic/trap cards the drop rates are generally even better than
  1/64 because S/A Tec takes significantly longer to achieve.
- The best (sometimes only) duelists to farm cards are the ones that
  make the most sense thematically. For example, you should farm Meteor
  B. Dragon from Atenza (Dragon-related high mage) or the strongest
  duelists who use it, eg Heishin and Seto 3rd, instead of farming it
  from the low meadow mage. This makes grinding more intuitive.
  Hopefully, you don't even have to look at the mods droplists in order
  to make your decisions while playing the game. It also makes the game
  progression smoother because it incentivizes you to always fight the
  toughest duelists you can handle rather than
  mindlessly grinding weaker opponents.
- If a duelist uses a card, then they can drop that card. However, this
  does not mean that the odds are good enough to be worth it. This is to
  make the game feel fairer and more intuitive.
- Some cards that were unobtainable or very rare in the game are
  restricted to the final gauntlet of the game. This means that you
  can't unlock the duelists that give them and grind them in free duel
  unless you beat the entire game first. For example, Meteor B. Dragon
  is easier to get before beating the game compared to Perfectly
  Ultimate Great Moth. This is because Meter B. Dragon is an iconic card
  from the vanilla game, whereas PUGM is not a card you would normally
  use to finish the game.
