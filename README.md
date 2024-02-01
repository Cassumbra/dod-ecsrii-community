# The Original Thread

Repo for community additions/tweaks to [Essential Core Skills Rebalance II](https://community.gaslampgames.com/threads/essential-core-skills-rebalance-ii-electric-bungalow.5624/) for [Dungeons of Dredmor](https://dungeonsofdredmor.com/).

# Changes to the original mod

None, yet!

# ECSRII Notes.txt

These are the original balance changes made by forum user Essence in the forums above. It has been edited and ordered for easier reading. It is recommended to read them in case you want more information about it.

## FIGHTER

### SHIELD BEARER [CHANGE]

- Shield Bearerer's Block and Piercing Resist lowered.
- Shield Bearer given 3 points of each basic damage type.

### DUAL WIELD [NERF]

- -20 EDR given on 1st level.
- Each successive level gives +5 EDR (net total of +0 over the entire tree.)
- The 3rd level of Deadshot gives less stats and now offers Inverse Minion Law, which checks to see how many enemies are around you each time you get hit and gives bonuses based on the number of enemies within the surrounding 8 squares.

### DEADSHOT [CHANGE]

The old Deadshot has been entirely ripped out and replaced with a brand new skill. New mechanics explained below:

### SWORDS [CHANGE]

The old Swords has been entirely ripped out and replaced with a brand new skill. Swords should be about nuking single opponents and countering attacks, with an 'off' level granting magic defense. Its key stat is Counter Chance.
**Level 1: Touche!**

- Activated attack; cooldown: 6.
- Attack inflicts an enduring, stacking debuff of -5 Counter, -5 Block, and -5 Dodge on your opponent.
- Passive: +3 Counter Chance and +1 Piercing Damage
**Level 2: Liechtenauer's Overhau**
- Activated attack; cooldown: 5.
- Attack inflicts extra damage equal to 2+(.25*Nimbleness) and causes Bleed.
- Passive: +1 Slashing Damage and +2 Counter Chance
**Level 3: Duelist Stance**
- Activated Buff. Removes Knight Stance. Grants +10 Counter, +10 Dodge, and +5 Melee Power.
- Also adds a playerHitEffectBuff that inflicts a 5-turn-long debuff on the player 100% of the time when hit: -2 Counter, -2 Dodge, and -1 Melee Power. The buff stacks once, the debuff stacks up to 20 times.
- Passive: +2 Counter Chance and +1 Enemy Dodge Reduction
**Level 4: Thibault's Trompenant**
- Activated attack; cooldown 9.
- Inflicts attack damage + 4+(.25*Nimbleness) Piercing Damage in a 3-square-long line in front of the player.
- Passive: +2 Slashing Damage and +1 Enemy Dodge Reduction
**Level 5: Knight Stance**
- Activated Buff. Removes Duelist Stance. +40 Block, +10 Counter, -100 Dodge, -10 EDR.
- Triggers a secondary, separately-removable buff called Parry Magic that grants +51 Magic Reflect with an Upkeep of 2 turns.
- Passive: +2 Counter Chance and +2 Enemy Dodge Reduction
**Level 6: Sword Poet**
- Passive. CounterBuff (100%) inflicts 8+(.25*Nimbleness) and causes bleeding and has a 50% chance to Paralyze for 2 turns.
- Passive: +6 Counter Chance, +1 Enemy Dodge Reduction and +3 Slashing Damage

### AXES [CHANGE]

The old Axes has been entirely ripped out and replaced with a brand new skill. Axes should be about nuking groups, using crits and increasing damage by continuously debuffing enemies. Its key stat is Critical Hit Chance.
**Level 1: Rend**

- Activated attack, cooldown: 6.
- Inflicts an enduring, stacking -4 Slashing Resistance bonus on the target.
- Passive: +3 Critical Hit Chance
**Level 2: Lumberjack Stance**
- Activated buff. Removes Barbarian Stance. Adds -5 Armor Absorption, +25 Critical Hit Chance, +3 Melee Power.
- Passive: +1 Slashing Damage and +2 Critical Hit Chance
**Level 3: Norwegian Axenado**
- Activated attack, cooldown 13.
- Attack deals normal damage + 4+(.15*Crit Chance) Slashing Damage to all 8 squares around the player.
- Passive: +3 Enemy Dodge Reduction
**Level 4: Barbarian Stance**
- Activated buff. Removes Lumberjack Stance. All normal attacks are modified to a 1-tile semicircle in front of the player.
- Targeted enemies take normal damage and are locked down and bleed. Other enemies hit take normal damage.
- Passive: +2 Slashing Damage +2 Critical Hit Chance
**Level 5: Viking King**
- Passive. Player gains a 100% CriticalBuff that inflicts an enduring, stacking -5 Armor Absorption debuff on your opponent.
- Passive: +3 Critical Hit Chance
**Level 6: Philosopher Of The Axe**
- Activated attack, cooldown: 17.
- Deals 8+(.25* Crit Chance) Existential Damage damage to all monsters within 2 squares of the player.

### MACES [CHANGE]

The old Maces has been entirely ripped out and replaced with a brand new skill. Maces should be about high damage numbers, knockbacks and slight debuffs. Its key stat is Crushing Damage.
**Level 1: I Am A Player And I Crush A Lot.**

- Activated attack, cooldown: 8.
- Deals normal weapon damage and inflicts Broken Bones (-2 Burliness, -4 Nimbleness, -2 Melee Power, -5 Block Chance, -3 Armor Absorption for 68 turns) and Daze (-40 Critical Hit Chance, -40 Dodge Chance, -30 Counter Chance, -20 Block Chance, -20 Magic Resistance, and mute for 8 turns).
- Passive: +2 Enemy Dodge Reduction, +1 Crushing Damage
**Level 2: Dwarven Handshake Stance**
- Activated buff. Removes Sundering Stance and Mjolnir Stance. -40 Crit, +4 Piercing damage, 25% to proc Unresistable Knock and 2+(.1 *Burliness) Blasting Damage .
- Passive: +1 Enemy Dodge Reduction +1 Crushing Damage +1 Piercing Damage
**Level 3: Sundering Stance**
- Activated buff. Removes Dwarven Handshake Stance and Mjolnir Stance.
- Attacks inflict a 4-turn stacking debuff of -2 Melee Power and -5 Enemy Dodge Reduction.
- Passive: +3 Crushing Damage
**Level 4: Ragnar's Meteor**
- Activated Attack, cooldown: 13.
- Hits the 6-square area immediately in front of the player for attack damage plus 4+(.2*Burliness) Blasting Damage and an Unresistable Knock.
- Passive: +2 Piercing Damage, +1 Crushing Damage
**Level 5: Hulk SMASH!**
- Activated attack, cooldown: 8.
- Deals additional 1.5\*Melee Power Crushing Damage damage and inflicts a 2-turn debuff on you such that when attacked, you take (.1* Melee Power) extra damage.
- Passive: +3 Enemy Dodge Reduction, +1 Crushing Damage
**Level 6: Mjolnir Stance**
- Activated buff. Removes Dwarven Handshake Stance and Sundering Stance.
- Grants +30 Burliness and a 5% targetHitEffectBuff that essentially casts Fulminaric Bolt on your melee victim.
- Passive: +3 Piercing Damage, +3 Crushing Damage, +1 Smithing.

### STAVES [CHANGE]

The old Staves has been entirely ripped out and replaced with a brand new (Wizard) skill. Staves should be about flexibility and damaging through Magic Power. Its key stat is Block Chance.
**Level 1: Not In The Face!**

- Activated buff. Removes Two Ends Stance and Long Stance.
- Grants +10 Block, +10 Magic Resist, and a 20% stun proc.
- Passive: +3 Block Chance.
**Level 2: Spirit Conduit**
- Activated attack, cooldown: 5.
- Inflicts 1+ (.2 * Magic Power) Transmutative damage and hits the enemy with a 2-turn -20 Magic Resist debuff.
- Passive: +1 Crushing Damage , +1 Enemy Dodge Reduction, +1 Block Chance .
**Level 3: This Thing Has Two Ends**
- Activated buff. Attacks deal an additional (.5*Melee Power) damage.
- All Staff-based special attacks (Spirit Conduit, Shillelagh, Priming Blow) have their effects increased by 50% while in this stance.
- Passive: +1 Enemy Dodge Reduction, +2 Block Chance
**Level 4: Shillelagh**
- Passive ability. All Staff strikes deal an additional 1+(.05* Magic Power) Aethereal damage.
- Passive: +1 :dmg_aethereal: , +1 Crushing Damage, +1 Block Chance
**Level 5: Priming Blow**
- Activated Attack, cooldown: 9.
- Deals normal damage and inflicts a debuff of -3 Aetherial Resist, -2 Conflagratory Resist, -3 Transmutative Resist, -2 Necromantic Resist and -2 Voltaic Resist permanently and stacking.
- Passive: +3 Enemy Dodge Reduction, +2 Block Chance
**Level 6: Shepard's Style**
- Activated buff. Removes Two Ends Stance and Not In The Face.
- Normal hits and Staff-based special attacks sweep in a 3x3 area centered at the target.
- The target and enemies behind it take double damage. Other enemies hit take normal damage.
- Passive: +3 Aetherial Damage and +6 Block Chance

### UNARMED [CHANGE]

The old Unarmed has been entirely ripped out and replaced with a brand new skill. Unarmed should be about knockbacks, stuns and multiplying dealt damage. Its key stat is Dodge Chance.
**Level 1: Brawlin' Stance**

- Activated buff. Removes Nerve Strike Stance.
- All attacks proc 1+(.2 *EDR) Crushing damage and Crushed Bones (see Maces level 1) 20% of the time.
- Passive: +1 Piercing Damage , +1 Enemy Dodge Reduction, +1 Dodge Chance .
**Level 2: Billy Quan Maneuver**
- Activated attack, cooldown: 4.
- Deals double melee damage, hits the target with an Unresistable Knock, and teleports you one square forward.
- Passive: +3 Dodge Chance.
**Level 3: Boot To The Head**
- Activated attack, cooldown 7.
- Normal attack damage procs Unresistable Knock and Daze (see Maces level 1).
- Passive: +2 Enemy Dodge Reduction, +2 Dodge Chance
**Level 4: Nerve Strike Stance**
- Activated buff. Removes Brawlin' Stance.
- Attacks have a 50% chance to proc, and triggers one of the following effects:
- Dazed (see Maces level 1)
- Stunned (-100 Dodge Chance, -100 Counter Chance, -20 Block Chance, -20 Magic Resistance, and paralyzed for 2 turns.)
- Paralysis for 2 turns
- Crushed Bones (see Maces level 1)
- Sundered (see Maces level 3)
- 6+(.2*EDR) Putrefying damage.
- Passive: +1 Piercing Damage, +1 Righteous Damage , +1 Dodge Chance
**Level 5: Two Feet Stomp The Diggle**
- Passive. Melee attacks have a 25% chance to proc Nice Combo!, which deals an additional melee attack that also has a 25% chance to proc Nice Combo! (Yes, this can chain indefinitely if you're absurdly lucky.)
- Passive: +2 Enemy Dodge Reduction, +3 Dodge Chance
**Level 6: Master Of The Dragon Foot Technique**
- Activated attack, cooldown: 24.
- Deals attack damage to all 4 surrounding squares. Then has a 66% chance to do it again, then another 66% chance to do it again, then a 67% chance to do it again. Then hits all 4 surrounding squares with an Unresistable Knock.
- Passive: +3 Righteous Damage , +5 Dodge Chance

### ARCHERY [CHANGE]

The old Archery has been entirely ripped out and replaced with a brand new skill. See next post for mechanics.

### THROWING [CHANGE]

The old Throwing has been entirely ripped out and replaced with a brand new (Warrior) skill. See next post for mechanics.

## WIZARD

### BLOOD MAGIC [CHANGE]

- Vital Siphon now returns at least 1 spell point each time it goes off (which is still only 30% of attacks), plus extra on Animals, Demons, and Others.
- Steal Spirit eliminated; replaced with Powered by Pain (27% chance to restore 1 mana when hit.)
- Steal Soul eliminated; replaced with Mass Exanguination (template 100 destroy corpses; gain 2-6 mana per corpse; 4% chance to Attract Unwanted Extraplanar Attention.)

### LEY LINE WALKING [CHANGE]

- Leyline Siphoning downtime increased to 42. Added a 6% chance to Attract Unwanted Extraplanar Attention.
- Channeler eliminated; replaced with Discover Ley Nexus (+5 Mana Regen and +10 Magic Resistance spellmine, each turn has a 1% chance to Attract Unwanted Extraplanar Attention.)

### MAGIC TRAINING [CHANGE]

- Certified Mage changed to You, D.M.A.:  +4 Savvy, +1 Sagacity.
- Wizarding Associate changed to Certamen Certified; gives 2 Savvy, 2 Sagacity, and ability to cast Certamen Circle (breakonmove, -100 dodge/counter, -10 EDR/crit, +50 Haywire/MRes/Mref, +8 Magic Regen.)
- Extraplanar Concenration given an 8% chance to Attract Unwanted Extraplanar Attention.
- Master of Magic changed to The Master Spell; gives 5 Sagacity, 5 Savvy, and a buff granting +100 Haywire and +10 Magic Power. Buff is removed on cast.

### VIKING WIZARDRY [CHANGE]

- Hand of Belimawr swapped with Unholy Warcry.
- Unholy Warcry's Blasting damage given scaling (.18 * Magic Power)
- Unholy Warcry's debuff increased to -20 Nimbleness, -5 Armor, -5 Melee Power.
- Unholy Warcry's fear effect reduced to 2 turns and a 44% chance of activation.

### VAMPIRISM [BUFF]

- Psychic Vampire's second 'gain mana' trigger was missing an amount="1". I added that back in.
- Transylvation now summons Blink Batty companions rather than regular Batties, and does so 3x more often (66% instead of 22%).

### FLESHSMITHING [BUFF]

- Meatshield now gives you a 17% chance to proc Fleshbore on enemies that hit you in combat.

### ASTROLOGY [BUFF]

- Solar Inscription is now a permanent mine (i.e. it will go off as many times as stepped on until it expires -- which is in 21 turns.)
- Syzygy, when cast, heals you for 5+(2* Sight Radius) HP.
Celestial Aegis no longer has any mana upkeep. (Compare to Mark of the Black Eyeliner, which does more stuff for less cost but has an upkeep -- I think this is good.)
- Celestial Aegis' brittle upped to 15.

## ROGUE

### ASSASSINATION [CHANGE]

- Slim Customer now gives a 12% on-Kill buff that grants +20 Sneakiness and a 100% Two Attacks, One Dagger proc until you attack or are attacked.
- Venomous Infusion is no longer an active skill; it now happens automatically 17% of the time when you get attacked in combat. It has been renamed Venomous Vengeance.
- Et Tu now scales to Nimbleness.

### FUNGAL ARTS [BUFF]

- The Toxic Spore Cloud created by Fungal Arts' Puffball is now a permanent mine (meaning it will continue to trigger each time a creature steps on a square within it's radius.) It also now deals 3+(.1 *Savvy) damage rather than a flat 3, and doesn't affect the caster.
- MiniToxicSporeCloud (fungal arts' level 4 proc) now deals 2+(.25*Savvy) damage (used to be a flat 2), is a permanent (until expired) mine, and doesn't affect the caster.
- Fungal Arts level 3 given 'Symbiotic Toadstools', a buff for pets only (target=adjacent).
- Mushroom Transmutation moved to Fungal Arts level 4.
- The final level of Fungal Arts can now correctly drop any kind of mushroom on a kill, and does so 8% of the time (used to be two separate 5% chances, so it's about the same)

### DODGE [BUFF]

- Transdimensional Dodging's downtime increased to 18, and it now triggers Froda's Jump Discontinuity when it's activated, so you can get out of closed rooms you might have gotten stuck in.
- Supremely Sly Side-Stepper now adds an additional (stacking) 30% chance to trigger Adventurer Aikido, because capstone (total rough effective percentage: 51%.)

### PERCEPTION [BUFF]

- Third Sight adds 1 damage that only affects walls.
- Third Sight now gives a 1-turn buff that allows a 100% proc of Luckiest Find on-kill.
- Eye Lasers now also trigger On Fire on the target.
- Eye Lasers now scale 3x Sight on Blasting Damage, 2x TrapSight on Conflagratory damage, and .2x EDR on Aethereal Damage.

### ARCHEOLOGY [NERF]

- It Belongs in a Museum swapped with Remember Your Charlemagne.

### GENERAL [FIX]

- All effects that used 'burn="1"' now trigger On Fire instead. (Ingition Bolt and a bunch of Voltaic Mine effects, really. Promethean had already been fixed by the GLGuys.)

## EXPANSION I

### BIG GAME HUNTER [BUFF and FIX]

- 'Lured' now inflicts a -15 penalty to Block, Dodge, and Counter in addition to it's other effects.
- BGH level 4 had a completely nonfunctional special attack ('Hunter's Strike') that was triggered on kill (meaning it tried to damage the creature that you had just killed.) I switched it from on-kill to on-hit, on-throw, and on-crossbow, and moved it to level 2. It deals 3+ (1/3 Sneakiness) Percing damage to Animals only on 50% of melee hits.
- Hunter's Strike had also apparently replaced BGH4's old 'more Grisly Trophies' onKill effect, which is specifically mentioned in the flavor text, so I added it back in.
- Also, since the flavor text of BGH4 says "we'll give it blood so we can kill it", I took the taxa restrictions off of the Butcher and Grisly Trophies effects that BGH4 gives, and then cut the %-to-proc by half considering they'll go off on everything you touch.

### DEMONOLOGIST [BUFF]

- Celestial Circle now inflicts -40 Nimbleness instead of -12.
- Abyssal Fire now lasts forever. On the downside, it now inflicts -4 Righteous, Hyperborean, and Existential Damage Resist on you, so it's not a brainless, leave-it-on-all-the-time thing.  It's still removable.  Also, it had two seperate on-hit procs which we know doesn't work, so I switched it to a single trigger that uses choosefromlist to pick one of the two relevant effects.
- Infernal Contract now has percentage chances to inflict it's various downsides, with the more nasty ones being less likely. (They used to be all 100%, so it's more of a gamble thing now.)
- Demonic Form now properly has a downtime (30, with a 13-turn duration, so you can spend just under half your time as a Demon), and to make up for it, gives a +3 Conflagratory damage bonus while in Demon Form. Also, you still have access to all Demonology skills when in Demon form.

### WEREDIGGLE [FIX/BUFF]

- Transforming into a Werediggle now heals 1+(.3 * maxHP) damage.
- Diggle Plague is now a proc that goes off on 17% of melee hits.
- Diggle Plague's DoT reactivated (it was borked because it was inside the buff tags, guys.)

### EMOMANCY [BUFF]

- Sigil of Whatever's damage scaling is doubled (to .2*magic power), and it's chance to paralyze is doubled (to 50%).
- Depressing Elemental Blast restored to it's ECSR1 status: it DoTs each enemy with 2+(.2*Magic Power) Existential damage and a Pacify each turn for 12 turns.

## EXPANSION II

### WARLOCKERY [FIX]

- Puissant Veil restored to it's intended status (blockBuff that procs a normal-sized Puissant Touch)
- Chronomantic Twist fixed.
- Manacalypse scaling brought in more proper line with the capstone buff-ending mana-eating beast that it truly is.

### ROGUE SCIENTIST [FIX/BUFF]

- Barometric Pulse Devices' "Vent Steam" mistakenly had 'usetimer="2", time="1"' rather than the opposite which is ovbiously what Ruigi intended.
- Thaumomechanical Rebreather's mana upkeep moved to 1/7 turns.
- Aetheric Death Ray's scaling to Wandcraft upped to 7.
- Aetheric Death Ray now correctly triggers On Fire rather than using the depreciated burn="1".

### PRACTICAL GEOLOGY [very minor BUFF]

- Basalt Skin's Timer increased to 16.
- Petrification's Armor increased to 50.  Piercing, Toxic, Putrefying, and Asphyxiative resists raised to 50.  Piercing and Conflagratory resists raised to 35.  Asphyxiative damage per tick increased so final damage (after the resist bump) remains the same as it was.

## EXPANSON III

### BANKSTERISM [BUFF]

- Percentage chance of triggering a random Bankster debuff on/when hit with Insurance Fraud active reduced to 1%.
- Percentage chance of triggering a random Bankster debuff on/when hit with Fiscal Hedge active reduced to 3%.
- Bailout now removes ALL Bankster debuffs and two random other debuffs (used to remove one iteration of each Bankster debuff and that's all...a horrible capstone.)

### EGYPTIAN MAGIC [NERF]

- Sandstorm now has a 50% chance of removing a random glyph when cast. Can randomly select glyphs you don't actually have, so unless you're going balls-out, actual chance of removal is much lower than 50%.
- Eye of Ra's various Blasts now have a 1% chance of removing a random glyph when activated. See previous note.

### COMMUNISM [BUFF]

- Warming Vodka added to the list of Random Commie Effects. There were too few positive effects on that list.
- Internal Contradiction now adds +1 Smithing.  Yep.
- Vanguard Party now only triggers debuffs on 1% of hits and being-hits. Also, non-melee-power bonuses from Vanguard Party are doubled.
- Iron Curtain Hyperborean Resistance increased to 8. (No more fur hats, dammit!)
- The Bomb now gives you a spell that creates a The Bomb and gives you a 999-turn unremovable debuff that prevents the bomb-creating ability from triggering as long as you have it.

### TOURIST [very minor BUFF]

- Handle Foreign Currencies upped to 125% normal Zorkmid gain.

### PARANORMAL INVESTIGATOR [minor BUFF]

- Close Encounter also adds a Knock effect on taxa="nothing" (i.e. objects only.)
- Alien Weapon now scales to Savvy rather than Magic Power.
