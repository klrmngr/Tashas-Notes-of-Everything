---
type: pc
race: "Giant"
class:
 - "Braxat"
subClass:
 - "CR 9"
cover: "Braxat.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/bam
---
###### Braxat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Braxat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor, intellect fortress) |
> | :FasHeart: HP | 162 (13d12 + 78) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 8 | 22 | 14 | 13 | 7 |
| **Mod** | +8 | -1 | +6 | +2 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Giant
**Damage Immunities:** acid; psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Intellect Fortress.** The braxat's AC includes its Intelligence modifier.


---

### Actions

**Multiattack.** The braxat makes two Greatclub attacks.

**Greatclub.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage.

**Acid Breath (Recharge 6).** The braxat exhales a 15-foot cone of acid. Each creature in the cone must make a DC 18 Constitution saving throw, taking 26 (4d12) acid damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Psionic Shield (3/Day).** When the braxat would be hit by an attack roll or a magic missile spell that originates from a source the braxat can see, the braxat can create an invisible barrier of magical force around itself that lasts until the start of its next turn. This barrier gives the braxat a +5 bonus to AC, including against the triggering attack, and prevents magic missile spells from damaging it.


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