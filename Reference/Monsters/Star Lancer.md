---
type: pc
race: "Celestial"
class:
 - "Star Lancer"
subClass:
 - "CR 2"
cover: "Star Lancer.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/2
  - source/mcv1sc
---
###### Star Lancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Star Lancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 15 | 10 | 13 | 8 |
| **Mod** | +4 | +2 | +2 | +0 | +1 | -1 |

**Speed:** 0 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Celestial, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +4
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** radiant

---

### Traits

**Flyby.** The star lancer doesn't provoke opportunity attacks when it flies out of an enemy's reach.


---

### Actions

**Horn.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage. If the star lancer moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 10 (3d6) piercing damage.

**Invisibility Cloak (3/Day).** The star lancer and one creature riding it (chosen by the star lancer) magically turn invisible. This effect lasts until the star lancer or a creature riding it attacks or casts a spell, or until the star lancer's concentration ends (as if concentrating on a spell). Any equipment worn or carried by the invisible creatures is also invisible for the duration of the Invisibility Cloak.


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