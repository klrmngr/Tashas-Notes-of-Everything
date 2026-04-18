---
type: pc
race: "Monstrosity (titan)"
class:
 - "Tromokratis"
subClass:
 - "CR 26"
cover: "Tromokratis.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/26
  - source/mot
---
###### Tromokratis
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Tromokratis.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 409 (21d20 + 189) |
> | :FasUserGroup: Race | Monstrosity (titan) |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 29 | 22 | 11 | 10 |
| **Mod** | +10 | +0 | +9 | +6 | +0 | +0 |

**Speed:** 30 ft., swim 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Int +14, Wis +8
**Damage Resistances:** cold; lightning; thunder
**Damage Immunities:** fire; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened; paralyzed; restrained

---

### Traits

**Amphibious.** Tromokratis can breathe air and water.

**Hearts of the Kraken (Mythic Trait; Recharges after a Short or Long Rest).** When Tromokratis is reduced to 0 hit points, it doesn't die or fall unconscious. Instead, the damage creates cracks in its carapace, revealing its hearts. Tromokratis has four hearts: two on its chest, one on its back, and one at the base of its tail. A heart has an AC of 22 and 100 hit points. It is immune to bludgeoning, piercing, and slashing damage from nonmagical attacks, and it is immune to all conditions. If it is forced to make a saving throw, treat its ability scores as 10 (+0). If it finishes a short or long rest, the carapace heals, any destroyed hearts regenerate, and the hearts are covered again. Tromokratis dies when all the hearts are destroyed.

**Legendary Resistance (3/Day).** If Tromokratis fails a saving throw, it can choose to succeed instead.

**Magic Weapons.** Tromokratis's weapon attacks are magical.

**Siege Monster.** Tromokratis deals double damage to objects and structures.

**Spell-Resistant Carapace.** Tromokratis has advantage on saving throws against spells, and any creature that makes a spell attack against Tromokratis has disadvantage on the attack roll.


---

### Actions

**Multiattack.** Tromokratis makes three attacks: one with its pincer, one with its tail, and one with its tentacle grasp.

**Pincer.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 20 (3d6 + 10) bludgeoning damage, and if the target is a creature, it is grappled (escape DC 26). Until the grapple ends, the target is restrained, and Tromokratis can't use this attack on anyone else.

**Tail.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 23 (3d8 + 10) bludgeoning damage, and if the target is a creature, it is knocked prone.

**Tentacle Grasp.** Melee Weapon Attack: +18 to hit, reach 20 ft., one creature. *Hit:* 20 (3d6 + 10) bludgeoning damage, and the target is grappled (escape DC 26). If the target doesn't escape by the end of its next turn, Tromokratis throws the target up to 60 feet in a straight line. The target lands prone and takes 21 (6d6) bludgeoning damage.

**Bite.** Melee Weapon Attack: +18 to hit, reach 5 ft., one target. *Hit:* 29 (3d12 + 10) piercing damage. If the target is a Large or smaller creature grappled by Tromokratis, that creature is swallowed, and the grapple ends. While swallowed, the creature is blinded and restrained, it has 3 against attacks and other effects outside Tromokratis, and it takes 42 (12d6) acid damage at the start of each of Tromokratis's turns. If Tromokratis takes 50 damage or more on a single turn from a creature inside it, Tromokratis must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of Tromokratis. If Tromokratis dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 15 feet of movement, exiting prone.


---

### Legendary Actions

### 

**Move.** Tromokratis moves up to half its speed.

**Tail.** Tromokratis makes one tail attack.

**Bite (Costs 3 Actions).** Tromokratis makes one bite attack.


---

### Mythic Actions

If Tromokratis's mythic trait is active, it can use the options below as legendary actions for 1 hour after using Hearts of the Kraken.

### 

**Rampage.** Tromokratis makes two attacks: one with its tail and one with its tentacle grasp.

**Coral Growth (Costs 2 Actions).** Each creature within 10 feet of Tromokratis must make a DC 25 Dexterity saving throw, taking 13 (3d8) slashing damage on a failed save, or half as much damage on a successful one. Until the start of its next turn, Tromokratis and its hearts gain a +2 bonus to AC.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```