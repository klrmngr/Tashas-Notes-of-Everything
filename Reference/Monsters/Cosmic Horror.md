---
type: pc
race: "Aberration"
class:
 - "Cosmic Horror"
subClass:
 - "CR 18"
cover: "Cosmic Horror.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/gargantuan
  - cr/18
  - source/bam
---
###### Cosmic Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Cosmic Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Aberration |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 280 (16d20 + 112) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 25 | 24 | 15 | 24 |
| **Mod** | +8 | +0 | +7 | +7 | +2 | +7 |

**Speed:** 50 ft., fly 100 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 12
**Languages:** Deep Speech, telepathy 240 ft.
**Saving Throws:** Int +13, Wis +8, Cha +13
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the horror fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The horror doesn't require air.


---

### Actions

**Multiattack.** The horror makes one Bite attack and two Tentacle attacks.

**Bite.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 22 (4d6 + 8) piercing damage.

**Tentacle.** Melee Weapon Attack: +14 to hit, reach 30 ft., one target. *Hit:* 18 (3d6 + 8) force damage, and if the target is a creature, it is grappled (escape DC 18). Until this grapple ends, the horror can't use this tentacle against other targets. The horror has 1d8 + 1 tentacles, each of which can grapple one target.

**Psychic Whispers (Recharge 5–6).** The horror emits dreadful whispers in a 60-foot-radius sphere centered on itself. Each creature in the sphere that isn't an Aberration must make a DC 21 Wisdom saving throw, taking 33 (6d10) psychic damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Crushing Tentacle.** The horror crushes one creature it is grappling. The grappled creature must make a DC 22 Constitution saving throw, taking 18 (3d6 + 8) force damage on a failed save, or half as much damage on a successful one.

**Poison Jet (Costs 2 Actions).** Foul gas squirts from the horror in a 30-foot line that is 5 feet wide. Each creature in the line must succeed on a DC 21 Constitution saving throw or take 14 (4d6) poison damage.

**Teleport (Costs 2 Actions).** The horror teleports, along with any creatures it is grappling, to an unoccupied space it can see within 120 feet of itself.


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