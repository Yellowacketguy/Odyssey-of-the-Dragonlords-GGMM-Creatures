# Odyssey-of-the-Dragonlords-GGMM-Creatures
A collection of creatures made for the D&amp;D 5e adventure Odyssey of the Dragonlords, using GiffyGlyph's Monster Maker.

## Using GiffyGlyph's Monster Maker

GiffyGlyph's Monster Maker is a set of rules for creating creatures in 5e that are meant to present a wider array of combat options and more engaging boss fights. The most recent version of this ruleset as of this writing can be found at https://drive.google.com/file/d/1DTdevsM641DQRA2sI1f6w1aPpFmlLIiM/view. I strongly recommend reading over this before using any of the creatures presented here, since most or all of them use mechanics that are unique to this module (which I will be referring to from here onwards as "GGMM"). You can easily create your own creatures using the GGMM app here: http://www.giffyglyph.com/monstermaker/app/

## Downloading and Reading the Files

The files in this repo are .json files. What this means is that you can download the file, go to the GGMM app linked above, navigate to the Vault tab, and click on the gear in the bottom-right corner. From the menu that appears, select "Import Monsters from .json", and upload the file. You should then have a copy of the monster's stat block, available for you to view and edit.

This readme file also contains my commentary on some of these creatures, and I recommend reading this before running these creatures in your own adventures.

## Commentary

These creatures are presented as .json files to be used in the GGMM app. These stat blocks, unless stated otherwise, do not have accurate values for their ability scores, saving throws, movement speeds, senses, or languages. These are instead taken from the creatures that these stat blocks are meant to convert.

A quick aside - I've given each of these creatures a name of the format "\[name\], \[title\]", so that my players know what to expect when they see that format. I've also for the most part tried to match the level of a creature to its CR in the adventure, but I take some liberties with this in some cases.

I've also used the shorthand "\[amount\] ongoing \[type\] damage" to mean "At the start of each of the target's turns, it takes \[amount\] \[type\] damage", and "(save ends)" to mean "the target can repeat this saving throw at the end of each of its turns, ending the effect on a success".

Lastly, note that these creatures were all designed to face a party of 5 PCs. If your group has a different number of PCs, adjust the creature's stats accordingly, using the GGMM rules (I believe this just requires adjusting the hp to match the party size - e.g. for a party of 4, multiply all bosses' max hp by 4/5).

### Ventis, the Tyrant

This was the first GGMM boss I threw at my party. I converted Ventis (originally a copper dragon) to a white dragon, primarily because I'd found some cool artwork for a white dragon and wanted an excuse to use it. In his first phase, Ventis is a Striker, making reckless attacks and prioritizing enemies who have recently dealt damage to him, and using his breath weapon as a devastating AoE attack. In his second phase, Ventis uses his breath weapon to enhance his scales with icy armor, becoming a Defender that tries to wear down his already-weak enemies and simply outlast them. He uses the last of his breath weapon to freeze the most-threatening enemy in place, turning the fight into a struggle for survival on both sides.

Ventis went fairly well for my first GGMM boss. The only major change I would make would be to have used Icy Tomb much sooner than I did in the fight, and maybe give him something else to do in phase 2 other than his basic attacks - maybe an attack that deals less damage but inflicts ongoing damage from frostbite.

### Hexia, the Traitor

This boss was built around supporting a mind-controlled Pythor. The first phase consists of Hexia playing support for Pythor, staying behind him and using her Commander trait to force him to attack the party (he otherwise refuses to attack, being too charmed to fight Hexia and too strong-willed to attack the party without direct control). The second phase is meant to be a shift in tactics, where she begins attacking the party directly, using a multitude of debilitating conditions to harry them while trying to finish them off. At this point, Pythor should be either unconscious or freed of the charm.

This fight was one of several that went sideways, not necessarily in a bad way, just in a way that resulted in a very unorthodox battle. One of the PCs had a feature that allowed them to remove charms (among other conditions), and the larger battle pivoted around a fight between this PC and Hexia for control of Pythor. Ultimately, the group ended up being able to maintain control of Pythor for the majority of the fight, which made it a lot easier than I had intended it to be, but I feel it was still a satisfying and unique encounter.

### Helios, the Rising Sun

This boss was probably my biggest mistake using GGMM. My original plan was to try something different for a dragon with this boss - give it a breath weapon without a cooldown condition, so it can spam it as much as it wants. Then I came up with the idea of instead giving it two breath weapons - a recharging fire breath, and an at-will radiant beam, the latter being a big part of why the dragon was once worshipped as a sun god. However, I failed to correct the damage for the fire breath, and for some reason had greatly reduced the base damage, so it ended up being severely underwhelming, aside from the blinding presence replacing frightening presence.

Overall, I think this boss was not a bad concept, being a gold dragon that can generate a seemingly-endless amount of fire and light between Immolate, Brilliant Beam, and Fire Breath. It just needs the damage to be correctly updated - below are some suggestions for changes that would fix this:

- Claw: damage becomes 2d6+3 slashing
- Immolate: damage becomes 15 ongoing fire damage
- Fire Breath: damage becomes 6d10 fire damage

### Diomedes, King of Eons

This boss was easily harder than any my party had fought before it, GGMM or otherwise. This androsphinx started the fight by laying into the party with claw attacks, and messing with them by teleporting them around (dealing force damage with this via telefrag) and plaguing them with traumatic flashbacks (leading to some fun RP material). Diomedes teleported the party to the Far Realm to fight grells after Phase 1 ended, resuming the fight in Phase 2 once they returned. By the end of Phase 3, the party was nearly dead, and completely depleted of resources. Note that my party was greatly helped by the fact that our warlock (the primary spellcaster in the group) had obtained a Rod of Absorption, and was able to negate Diomedes' Counterspell.

My original plan for Diomedes was actually even harder than this - it had a second reaction, and a 1/day ability that it would only use in Phase 3. If you want to make this boss even more brutal than it already is, consider adding the following features, which borrow mechanics from the lesser sphinxes introduced in the adventure.

- Time Loop (1/day) (Phase 3 Only): A creature within 120' of the sphinx must make a DC 17 CHA save or become trapped in a time loop (save ends). While trapped in the time loop, the target takes 20 psychic damage at the start of its turn, it makes attack rolls with disadvantage, and at the end of its turn it teleports to the space it was in at the start of its turn.

- Rewind (Reaction) (Phase 3 Only): Diomedes forces a creature not afflicted by his Time Loop ability to repeat an action it just performed, undoing the results of the action before making it repeat the attempted action.

### Hezzebal, the Forgotten

This boss was about as brutal as the one before it. As a high-level Striker, Hezzebal had incredible amounts of damage, and repeatedly downed party members, even killing one PC (she got better). I made the executive decision to shut off his damaging aura after he first used Necrotic Surge, since it was absurdly punishing to the melee characters in the party, and didn't present any engaging counterplay. I'd recommend you similarly remove this feature if you use this creature in your own game.

### Lutheria, the Empress / Lutheria, Lady of Dreams

Lutheria was a fairly brutal fight, but for very different reasons than the other bosses were. As our party had a Doomed One in it (a role in the adventure, one of which each player chose for their character), Lutheria spent the fight focusing all of her attacks on this character, and the battle became a sort of escort mission, with the party doing their utmost to defend the poor monk while trying to defeat the titan empress. The party also had an opportunity to burn her uses of Inspiration in a game of chance against her, meaning that she did not have full access to this resource during the fight.

Lutheria's first phase is a Striker, using her Emerald Scythe and her Blight spell to deal massive damage to the party, and occasionally using Madness or Hideous Laughter to try and weaken the most effective attackers. However, my party had fairly good success with saving throws, and were able to negate most of these attempts.

The titan's second phase is a Scout, dancing about the battlefield while her scythe hovers above, waiting to descend. I ended up changing the ability Curtain Call in particular to be Cooldown 3, instead of Recharge 5/6, so that the party knows exactly when it will strike next, and have to rush Lutheria down before it does. In the meantime, the goddess attacks by using Maddening Touch, Lullaby, and Invitation to Dance, relying on her scythe's Curtain Call as her primary source of damage.

In her third and final phase, Lutheria initially appears dead, but has actually turned invisible and begun the final stage of her attack. Her scythe destroyed, Lutheria relies wholly on her powers of madness and nightmares to destroy the party. She alternates between turning invisible, and using one of her attacks or spells - spreading blindness via Blinding Darkness, striking with her horrific claws, or using Nightmare Unleashed to show the party her true form.

This last phase ended up being slightly weaker than I'd intended, as a Lurker that has to waste every other action turning invisible without moving. I feel like this might've gone a bit better if she had been able to move as part of her Vanish action, or even remained constantly invisible throughout the fight, this phase might've been more climactic. However, as it is, I think this fight was still really tense and satisfying overall.

### Talieus, Son of Sydon

This boss and the next felt a little underwhelming. Talieus is a skilled smith, and wears a suit of magical armor, wielding a powerful hammer in combat. I gave him a few spells, loosely basing him on the Young Empyrean stat block provided in the adventure. This is also when I started experimenting with bosses that use spellcasting as part of their multiattack, to create hybrid casters that can use weapons and spellcraft to fight the party. Talieus is also capable of using a powerful Storm Rune, which expels his hammer's magic in two ways - a wave of thunder that strikes everyone near him, and bolts of lightning that strike distant targets as well. 

Overall, this boss felt somewhat underwhelming, but I suppose that was to be expected of its lower level (relative to previous bosses) and the fact that it was fought right after dealing with a trio of young dragons. This boss served well as a testing ground for hybrid spell/weapon boss mechanics.

### Chalcia, Favorite of Sydon

This boss also felt a tad disappointing to run, but worked out fine otherwise. Chalcia wields the Starmetal Solar Axe, which is from the Griffon's Saddlebag. Its stats as a magic weapon can be found here: https://www.reddit.com/r/TheGriffonsSaddlebag/comments/dnug7x/the_griffons_saddlebag_starmetal_solar_axe_weapon/

Chalcia fights by transforming the axe back and forth between a greataxe and two handaxes, and using her Smite spells with her Paragon Actions in order to empower her future attacks. I tried to balance this by making the Smite spells empower her next successful attack by an amount comparable to her intended damage per action - about half her damage value, plus a rider effect that makes the Smite useful beyond being a simple damage increase.

I think Chalcia ended up being a pretty balanced boss for her level, the issue is that she was fought right after facing Sydon's first two phases, so she felt if anything like a respite from that boss's damage output and insane defenses. Making her a Striker instead of a Scout might have been a more effective way to make her feel like a genuine threat after facing Sydon.

### Icarus, the King's Dragon

This boss was rather fun to play, although I feel I may have mishandled the twist at the end of this fight. Icarus is presented here as a really simple boss fight, little different from the default stat block for an ancient silver dragon, save for having the Reckless and Rampage traits.

The main gimmick of this boss is the fact that Icarus gains a level of exhaustion at the start of each of his turns (not represented in the stat block), eventually dying due to this. When I ran Icarus, I had the third level of exhaustion cause him to lose 720 max health and current health, but this resulted in him being left with so little hp that he was eliminated in a couple more attacks - barely giving him time to change from attacking the party to begging for help, as I had intended for him to do. If I were to run this again, I'd instead leave the boss's current health untouched, reducing it only if it was above 720 before reaching three levels of exhaustion.

### Sydon, the Emperor / Sydon, Lord of Storms

This boss worked fairly well, at least for the first two phases. For the first phase of the fight, Sydon is a Defender, with very high AC and a hard-hitting Glaive attack. In the second phase, he switches to a Striker, imbuing his Glaive with lightning and gaining the ability to stun enemies. Finally, in the third phase, Sydon hovers high above the ground as a Sniper, dealing passive damage to everyone via the storm he conjures, while firing off devastating spells.

Although the first two phases felt satisfying, the third phase was definitely too fragile, without any significant ability to maintain distance from his attackers. I had intended for this boss to stay high up in the air and let the storm wear the party down, but they were able to stay on top of him far too easily. Starting the storm in Blizzard might have made it easier for him to get some distance, as it would have obscured him from the party.

Additionally, for this and the next boss, the party had very powerful allies - four dragons, a flying unicorn, and a walking colossus. Without these, this boss would likely have been far more difficult, and the following boss would have been almost impossible.

### Kentimane, the First Titan

This boss ended up being an unusual one, in that it had so much potential damage that the only way to safely engage it was to try and finish it off while keeping it stunned via our monk's Stunning Blows. If anything, this highlighted how absurdly powerful that ability is in a game that prominently features boss fights, and I am planning on reducing its effectiveness to compensate for how strong it is in this case. That said, I think that for Kentimane in particular, letting him continue to attack through his hands could have been one way to keep the party from feeling too safe while he was stunned, or giving him some way to try and shrug off being stunned.

### Zakroth's Prison Fort

This segment of the adventure marked the start of my total conversion of the module to GGMM. I created my own versions of Zakroth, Belladonna, the minotaur hero, a higher-level maenad, the gigantes, and the centaurs. My party never fought any of the centaurs, so I can't say how they would've worked as enemies, but as an ally for a couple encounters, the centaur druid worked very well. The gigantes witches made for an interesting enemy, as my party developed their strategies around keeping those away from the frontline. The minotaur and the maenads were not much of a threat, but they served their purpose - draining some of the party's resources and bringing back a familiar foe. In the boss fight (Zakroth, Belladonna, and two gigantes witches), Zakroth went down fairly quickly as he got hit by Hold Monster and the witches were unable to help him due to both failing saves against Confusion. However, once Zakroth was down, Belladonna quickly became a deadly threat, nearly wiping out the party herself with repeated uses of Cone of Cold. Overall I think this conversion worked very well, and made for the first genuinely close fight since our second session of the game.

### Tomb of Karpathos

For this segment of the adventure, I aimed to create a tense dungeon crawl, where the players would never feel like they had all the answers and that they couldn't afford to just stop and rest whenever they wanted. The adventure is already designed with a lot more emphasis on flavor than on difficulty - the vampire spawn bound inside pillars and paralyzed by millstone amulets pose little to no threat, but their presence kept my players on edge: should they free the vampires *just* to kill them? Would they regret leaving those undead behind them, or would killing them enrage the shadows that lingered over their tombs?

As far as combat went, on the one hand it felt much easier than I'd wanted, but on the other hand the pacing of the dungeon helped to make up for that. Aside from the keledones (which were *brutal*, and dealt massive damage to my entire party before someone cast *Silence* and I ruled that, without any viable attack options, the keledones would freeze up and do nothing, being unthinking constructs), the enemies were fairly easy - the dread wolves hit hard but rarely hit, the vampire spawn were *made* to be minions so they went under in droves, and the two elites struggled to do meaningful damage against a party that had an Amazon Ranger with the Pressure Points ability.

I made a small change that I think made this adventure much more interesting than it otherwise would have been - I decided in advance that Karpathos and Nemosyne each can use each other's coffins to recover, putting my party on a strict time limit once they'd "killed" Karpathos - reach Nemosyne's tomb within an hour, or potentially face the two side-by-side. My players made the choice to press on, despite suffering a lot of damage in fighting the keledones, and they paid for this when the nuckles attacked after the party had wiped the dungeon without resting, and led a horde of zombies to attack them. This stretched my party to their limits, as they used the last of their resources to overcome the attack, but in the end they succeeded.

Overall, I don't think that my choices for the creatures in this dungeon were especially successful, or at the very least their success in design is heavily dependent on circumstance. The dread wolves never benefited from Press the Attack, but maybe they would have if they had been fought after the keledones. Nemosyne got paralyzed for the entire fight after getting one attack off, but maybe she would have been a more interesting fight had Pressure Points not been a thing the party had. My party never suffered terribly for hit points between encounters, but this was only because they had a Scholar (Benjamin Huffman's homebrew) on their team as a powerful utility support. However, I think that the design choices I made for running this dungeon - presenting an incentive for pushing on without resting, letting vampires use each other's coffins, and setting up scenarios where the party faced enemies coming from multiple directions and had to choose between retreating or trying to push through the weaker of the two fronts - made for a refreshing change from the pace of our game, and even if it wasn't especially challenging, the segment was at least distinctive.
