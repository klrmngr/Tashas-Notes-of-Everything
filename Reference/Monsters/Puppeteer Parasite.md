---
type: pc
race: "Aberration"
class:
 - "Puppeteer Parasite"
subClass:
 - "CR 3"
cover: "Puppeteer Parasite.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/3
  - source/mcv1sc
---
###### Puppeteer Parasite
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Puppeteer Parasite.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 71 (11d4 + 44) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 15 | 18 | 16 | 10 | 3 |
| **Mod** | -4 | +2 | +4 | +3 | +0 | -4 |

**Speed:** 10 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** telepathy 30 ft.
**Saving Throws:** Dex +4, Con +6, Wis +2
**Skills:** Stealth +4
**Damage Vulnerabilities:** radiant
**Damage Resistances:** fire; necrotic; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Unusual Nature.** The parasite doesn't require air or sleep.


---

### Actions

**Cling.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 12 (3d6 + 2) necrotic damage, and the parasite attaches to the target. While attached, the parasite can't make Cling attacks. The parasite can detach itself by spending 5 feet of its movement. As an action, a creature within reach of the parasite can try to detach it, doing so with a successful DC 14 Strength check.

**Consume Life.** The parasite deals 12 (3d6 + 2) necrotic damage to one creature it is physically attached to, provided that creature isn't a Construct or an Undead. The parasite regains hit points equal to the damage taken.


---

### Bonus Actions

**Suggestion (Psionics; 1/Day).** The parasite casts the suggestion spell, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 13).


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