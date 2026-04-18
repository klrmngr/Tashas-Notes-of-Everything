---
type: pc
race: "Celestial"
class:
 - "Mercane"
subClass:
 - "CR 5"
cover: "Mercane.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/5
  - source/bam
---
###### Mercane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Mercane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13 (mage armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 18 | 16 | 15 |
| **Mod** | +3 | +0 | +2 | +4 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Giant, telepathy 60 ft. (see also Mercane telepathy)
**Saving Throws:** Int +7, Wis +6, Cha +5
**Skills:** Insight +9, Perception +6, Persuasion +5

---

### Traits

**Mercane Telepathy.** The mercane can communicate telepathically with any other mercane it knows, regardless of the distance between them.


---

### Actions

**Multiattack.** The mercane makes three Psi-Imbued Blade attacks.

**Psi-Imbued Blade.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage, and if the target is a creature, it must succeed on a DC 15 Wisdom saving throw or be frightened of the mercane until the end of the target's next turn.


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