---
type: pc
race: "Dragon"
class:
 - "Lunar Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Lunar Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/bam
---
###### Lunar Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Lunar Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 16 | 6 | 10 | 9 |
| **Mod** | +2 | +1 | +3 | -2 | +0 | -1 |

**Speed:** 40 ft., burrow 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Con +5, Wis +2
**Skills:** Perception +4, Stealth +5
**Damage Immunities:** cold

---

### Traits

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and leaves a 5-foot-diameter tunnel in its wake.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 3 (1d6) cold damage.

**Cold Breath (Recharge 5–6).** The dragon exhales a blast of frost in a 15-foot cone. Each creature in the cone must make a DC 13 Constitution saving throw. On a failed save, the creature takes 13 (3d8) cold damage, and its speed is halved until the end of its next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


---

### Bonus Actions

**Phase (2/Day).** The dragon becomes partially incorporeal for as long as it maintains concentration on the effect (as if concentrating on a spell). While partially incorporeal, the dragon has resistance to bludgeoning, piercing, and slashing damage.


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