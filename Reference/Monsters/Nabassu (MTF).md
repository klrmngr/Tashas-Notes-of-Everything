---
type: pc
race: "Fiend (demon)"
class:
 - "Nabassu"
subClass:
 - "CR 15"
cover: "Nabassu.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/15
  - source/mtf
---
###### Nabassu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Nabassu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 190 (20d8 + 100) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 14 | 21 | 14 | 15 | 17 |
| **Mod** | +6 | +2 | +5 | +2 | +2 | +3 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +11, Dex +7
**Skills:** Perception +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Shadows.** The nabassu darkens the area around its body in a 10-foot radius. Nonmagical light can't illuminate this area of dim light.

**Devour Soul.** A nabassu can eat the soul of a creature it has killed within the last hour, provided that creature is neither a construct nor an undead. The devouring requires the nabassu to be within 5 feet of the corpse for at least 10 minutes, after which it gains a number of Hit Dice (d8s) equal to half the creature's number of Hit Dice. Roll those dice, and increase the nabassu's hit points by the numbers rolled. For every 4 Hit Dice the nabassu gains in this way, its attacks deal an extra 3 (1d6) damage on a hit. The nabassu retains these benefits for 6 days. A creature devoured by a nabassu can be restored to life only by a wish spell.

**Magic Resistance.** The nabassu has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The nabassu's weapon attacks are magical.


---

### Actions

**Multiattack.** The nabassu uses its Soul-Stealing Gaze and makes two attacks: one with its claws and one with its bite.

**Claws.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) slashing damage.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 32 (4d12 + 6) piercing damage.

**Soul-Stealing Gaze.** The nabassu targets one creature it can see within 30 feet of it. If the target can see the nabassu and isn't a construct or an undead, it must succeed on a DC 16 Charisma saving throw or reduce its hit point maximum by 13 (2d12) damage and give the nabassu an equal number of temporary hit points. This reduction lasts until the target finishes a short or long rest. The target dies if its hit point maximum is reduced to 0, and if the target is a humanoid, it immediately rises as a [[Ghoul]] under the nabassu's control.


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