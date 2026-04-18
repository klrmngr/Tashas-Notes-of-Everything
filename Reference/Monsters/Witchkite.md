---
type: pc
race: "Dragon (warlock)"
class:
 - "Witchkite"
subClass:
 - "CR 15"
cover: "Witchkite.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/mcv4ec
---
###### Witchkite
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Witchkite.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (warlock) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 220 (21d12 + 84) |
> | :FasUserGroup: Race | Dragon (warlock) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 18 | 15 | 17 | 19 |
| **Mod** | +6 | +0 | +4 | +2 | +3 | +4 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Draconic
**Saving Throws:** Dex +5, Wis +8, Cha +9
**Skills:** Arcana +7, Perception +8, Stealth +5
**Damage Resistances:** fire; psychic

---

### Traits

**Legendary Resistance (3/Day).** If the witchkite fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The witchkite makes two Rend attacks and uses Malevolent Flare once.

**Rend.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) slashing damage.

**Malevolent Flare.** The witchkite spits magical, green-tinged flame at one creature it can see within 60 feet of itself. The target must make a DC 17 Dexterity saving throw. On a failed save, the target takes 22 (5d8) fire damage and suffers one of the following effects of the witchkite's choice:
- The target must use its reaction to make a melee attack against another creature of the witchkite's choice that is within the target's reach.
- The target takes 13 (2d12) psychic damage.
On a successful save, the target takes half as much damage only.


---

### Reactions

**Enchanting Gaze.** When a creature the witchkite can see moves within 10 feet of it, the witchkite emits an enchanting gaze at the creature. The creature must succeed on a DC 17 Wisdom saving throw or take 10 (3d6) psychic damage and have the charmed condition until the end of its next turn.

**Retribution.** Immediately after taking damage from a melee attack, the witchkite makes one Rend attack against the attacker.


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