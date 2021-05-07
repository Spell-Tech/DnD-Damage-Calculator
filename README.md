# DnD-Damage-Calculator

This program is meant to calculate the average damage of spells
in D&D 5e. If you choose, it will factor Empowered Spell,
Elemental Adept, and/or Flames of Phlegethos into the damage
calculations. The program does this by simulating random dice rolls
a specified number of times and taking the average result of each
simulation. If Empowered spell isn't used for the spell, then the
average result is instead calculated using probability.

It is worth noting that this program operates under my interpretation
of how these features interact with each other, which is as follows:
If you reroll a damage die with either Empowered Spell or Flames of
Phlegethos, you have to keep that new roll. You can't, for example,
reroll with Empowered to get a 1 and then reroll again with Flames. If
you roll a 1 on any damage die, you can treat it as a 2 with Elemental
Adept, regardless of whether or not it has been rerolled already.
