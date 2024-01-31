

FIGHTER

SHIELD BEARER [CHANGE]
Shield Bearerer's Block and Piercing Resist lowered. 
Shield Bearer given 3 points of each basic damage type. 

DUAL WIELD [NERF]
-20 EDR given on 1st level.
Each successive level gives +5 EDR (net total of +0 over the entire tree.)
The 3rd level of Deadshot gives less stats and now offers Inverse Minion Law, which checks to see how many enemies are around you each time you get hit and gives bonuses based on the number of enemies within the surrounding 8 squares.

DEADSHOT [CHANGE]
The old Deadshot has been entirely ripped out and replaced with a brand new skill. See next post for mechanics. 

SWORDS [CHANGE]
The old Swords has been entirely ripped out and replaced with a brand new skill. See next post for mechanics. 

AXES [CHANGE]
The old Axes has been entirely ripped out and replaced with a brand new skill. See next post for mechanics. 

MACES [CHANGE]
The old Maces has been entirely ripped out and replaced with a brand new skill. See next post for mechanics. 

STAVES [CHANGE]
The old Staves has been entirely ripped out and replaced with a brand new (Wizard) skill. See next post for mechanics.

UNARMED [CHANGE]
The old Unarmed has been entirely ripped out and replaced with a brand new skill. See next post for mechanics. 

ARCHERY [CHANGE]
The old Archery has been entirely ripped out and replaced with a brand new skill. See next post for mechanics. 

THROWING [CHANGE]
The old Throwing has been entirely ripped out and replaced with a brand new (Warrior) skill. See next post for mechanics. 



WIZARD

BLOOD MAGIC [CHANGE]
Vital Siphon now returns at least 1 spell point each time it goes off (which is still only 30% of attacks), plus extra on Animals, Demons, and Others.
Steal Spirit eliminated; replaced with Powered by Pain (27% chance to restore 1 mana when hit.) 
Steal Soul eliminated; replaced with Mass Exanguination (template 100 destroy corpses; gain 2-6 mana per corpse; 4% chance to Attract Unwanted Extraplanar Attention.) 

LEY LINE WALKING [CHANGE]
Leyline Siphoning downtime increased to 42. Added a 6% chance to Attract Unwanted Extraplanar Attention. 
Channeler eliminated; replaced with Discover Ley Nexus (+5 Mana Regen and +10 Magic Resistance spellmine, each turn has a 1% chance to Attract Unwanted Extraplanar Attention.)

MAGIC TRAINING [CHANGE]
Certified Mage changed to You, D.M.A.:  +4 Savvy, +1 Sagacity.
Wizarding Associate changed to Certamen Certified; gives 2 Savvy, 2 Sagacity, and ability to cast Certamen Circle (breakonmove, -100 dodge/counter, -10 EDR/crit, +50 Haywire/MRes/Mref, +8 Magic Regen.)
Extraplanar Concenration given an 8% chance to Attract Unwanted Extraplanar Attention.
Master of Magic changed to The Master Spell; gives 5 Sagacity, 5 Savvy, and a buff granting +100 Haywire and +10 Magic Power. Buff is removed on cast. 

VIKING WIZARDRY [CHANGE]
Hand of Belimawr swapped with Unholy Warcry.
Unholy Warcry's Blasting damage given scaling (.18 * Magic Power)
Unholy Warcry's debuff increased to -20 Nimbleness, -5 Armor, -5 Melee Power.
Unholy Warcry's fear effect reduced to 2 turns and a 44% chance of activation. 

VAMPIRISM [BUFF]
Psychic Vampire's second 'gain mana' trigger was missing an amount="1". I added that back in. 
Transylvation now summons Blink Batty companions rather than regular Batties, and does so 3x more often (66% instead of 22%). 

FLESHSMITHING [BUFF]
Meatshield now gives you a 17% chance to proc Fleshbore on enemies that hit you in combat. 

ASTROLOGY [BUFF]
Solar Inscription is now a permanent mine (i.e. it will go off as many times as stepped on until it expires -- which is in 21 turns.)
Syzygy, when cast, heals you for 5+(2* Sight Radius) HP.
Celestial Aegis no longer has any mana upkeep. (Compare to Mark of the Black Eyeliner, which does more stuff for less cost but has an upkeep -- I think this is good.)
Celestial Aegis' brittle upped to 15.




ROGUE

ASSASSINATION [CHANGE]
Slim Customer now gives a 12% on-Kill buff that grants +20 Sneakiness and a 100% Two Attacks, One Dagger proc until you attack or are attacked.
Venomous Infusion is no longer an active skill; it now happens automatically 17% of the time when you get attacked in combat. It has been renamed Venomous Vengeance.
Et Tu now scales to Nimbleness.

FUNGAL ARTS [BUFF]
The Toxic Spore Cloud created by Fungal Arts' Puffball is now a permanent mine (meaning it will continue to trigger each time a creature steps on a square within it's radius.) It also now deals 3+(.1 * Savvy) damage rather than a flat 3, and doesn't affect the caster.
MiniToxicSporeCloud (fungal arts' level 4 proc) now deals 2+(.25*Savvy) damage (used to be a flat 2), is a permanent (until expired) mine, and doesn't affect the caster.
Fungal Arts level 3 given 'Symbiotic Toadstools', a buff for pets only (target=adjacent). 
Mushroom Transmutation moved to Fungal Arts level 4.
The final level of Fungal Arts can now correctly drop any kind of mushroom on a kill, and does so 8% of the time (used to be two separate 5% chances, so it's about the same)

DODGE [BUFF]
Transdimensional Dodging's downtime increased to 18, and it now triggers Froda's Jump Discontinuity when it's activated, so you can get out of closed rooms you might have gotten stuck in. 
Supremely Sly Side-Stepper now adds an additional (stacking) 30% chance to trigger Adventurer Aikido, because capstone (total rough effective percentage: 51%.) 

PERCEPTION [BUFF]
Third Sight adds 1 damage that only affects walls. 
Third Sight now gives a 1-turn buff that allows a 100% proc of Luckiest Find on-kill. 
Eye Lasers now also trigger On Fire on the target. 
Eye Lasers now scale 3x Sight on Blasting Damage, 2x TrapSight on Conflagratory damage, and .2x EDR on Aethereal Damage.

ARCHEOLOGY [NERF]
It Belongs in a Museum swapped with Remember Your Charlemagne.

GENERAL [FIX] 
All effects that used 'burn="1"' now trigger On Fire instead. (Ingition Bolt and a bunch of Voltaic Mine effects, really. Promethean had already been fixed by the GLGuys.)



EXPANSION I:

BIG GAME HUNTER [BUFF and FIX]
'Lured' now inflicts a -15 penalty to Block, Dodge, and Counter in addition to it's other effects. 
BGH level 4 had a completely nonfunctional special attack ('Hunter's Strike') that was triggered on kill (meaning it tried to damage the creature that you had just killed.) I switched it from on-kill to on-hit, on-throw, and on-crossbow, and moved it to level 2. It deals 3+ (1/3 Sneakiness) Percing damage to Animals only on 50% of melee hits. 
Hunter's Strike had also apparently replaced BGH4's old 'more Grisly Trophies' onKill effect, which is specifically mentioned in the flavor text, so I added it back in.
Also, since the flavor text of BGH4 says "we'll give it blood so we can kill it", I took the taxa restrictions off of the Butcher and Grisly Trophies effects that BGH4 gives, and then cut the %-to-proc by half considering they'll go off on everything you touch. 

DEMONOLOGIST [BUFF]
Celestial Circle now inflicts -40 Nimbleness instead of -12. 
Abyssal Fire now lasts forever. On the downside, it now inflicts -4 Righteous, Hyperborean, and Existential Damage Resist on you, so it's not a brainless, leave-it-on-all-the-time thing.  It's still removable.  Also, it had two seperate on-hit procs which we know doesn't work, so I switched it to a single trigger that uses choosefromlist to pick one of the two relevant effects.
Infernal Contract now has percentage chances to inflict it's various downsides, with the more nasty ones being less likely. (They used to be all 100%, so it's more of a gamble thing now.)
Demonic Form now properly has a downtime (30, with a 13-turn duration, so you can spend just under half your time as a Demon), and to make up for it, gives a +3 Conflagratory damage bonus while in Demon Form. Also, you still have access to all Demonology skills when in Demon form. 

WEREDIGGLE [FIX/BUFF]
Transforming into a Werediggle now heals 1+(.3 * maxHP) damage. 
Diggle Plague is now a proc that goes off on 17% of melee hits. 
Diggle Plague's DoT reactivated (it was borked because it was inside the buff tags, guys.)

EMOMANCY [BUFF] 
Sigil of Whatever's damage scaling is doubled (to .2*magic power), and it's chance to paralyze is doubled (to 50%).
Depressing Elemental Blast restored to it's ECSR1 status: it DoTs each enemy with 2+(.2*Magic Power) Existential damage and a Pacify each turn for 12 turns. 



EXPANSION II:

WARLOCKERY [FIX]
Puissant Veil restored to it's intended status (blockBuff that procs a normal-sized Puissant Touch)
Chronomantic Twist fixed.
Manacalypse scaling brought in more proper line with the capstone buff-ending mana-eating beast that it truly is. 

ROGUE SCIENTIST [FIX/BUFF]
Barometric Pulse Devices' "Vent Steam" mistakenly had 'usetimer="2", time="1"' rather than the opposite which is ovbiously what Ruigi intended. 
Thaumomechanical Rebreather's mana upkeep moved to 1/7 turns. 
Aetheric Death Ray's scaling to Wandcraft upped to 7. 
Aetheric Death Ray now correctly triggers On Fire rather than using the depreciated burn="1". 

PRACTICAL GEOLOGY [very minor BUFF]
Basalt Skin's Timer increased to 16. 
Petrification's Armor increased to 50.  Piercing, Toxic, Putrefying, and Asphyxiative resists raised to 50.  Piercing and Conflagratory resists raised to 35.  Asphyxiative damage per tick increased so final damage (after the resist bump) remains the same as it was. 


EXPANSON III:

BANKSTERISM [BUFF]
Percentage chance of triggering a random Bankster debuff on/when hit with Insurance Fraud active reduced to 1%.
Percentage chance of triggering a random Bankster debuff on/when hit with Fiscal Hedge active reduced to 3%.
Bailout now removes ALL Bankster debuffs and two random other debuffs (used to remove one iteration of each Bankster debuff and that's all...a horrible capstone.) 

EGYPTIAN MAGIC [NERF]
Sandstorm now has a 50% chance of removing a random glyph when cast. Can randomly select glyphs you don't actually have, so unless you're going balls-out, actual chance of removal is much lower than 50%.
Eye of Ra's various Blasts now have a 1% chance of removing a random glyph when activated. See previous note. 

COMMUNISM [BUFF]
Warming Vodka added to the list of Random Commie Effects. There were too few positive effects on that list. 
Internal Contradiction now adds +1 Smithing.  Yep. 
Vanguard Party now only triggers debuffs on 1% of hits and being-hits. Also, non-melee-power bonuses from Vanguard Party are doubled.
Iron Curtain Hyperborean Resistance increased to 8. (No more fur hats, dammit!)
The Bomb now gives you a spell that creates a The Bomb and gives you a 999-turn unremovable debuff that prevents the bomb-creating ability from triggering as long as you have it.

TOURIST [very minor BUFF]
Handle Foreign Currencies upped to 125% normal Zorkmid gain. 

PARANORMAL INVESTIGATOR [minor BUFF]
Close Encounter also adds a Knock effect on taxa="nothing" (i.e. objects only.) 
Alien Weapon now scales to Savvy rather than Magic Power. 