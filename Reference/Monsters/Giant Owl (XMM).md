---
type: pc
race: "Celestial"
class:
 - "Giant Owl"
subClass:
 - "CR 1/4"
cover: "Giant Owl.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/1-4
  - source/xmm
---
###### Giant Owl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Owl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 19 (3d10 + 3) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 15 | 12 | 10 | 14 | 10 |
| **Mod** | +1 | +2 | +1 | +0 | +2 | +0 |

**Speed:** 5 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** Celestial; understands Common, Elvish, and Sylvan but can't speak them
**Saving Throws:** Wis +4
**Skills:** Perception +6, Stealth +6
**Damage Resistances:** necrotic; radiant

---

### Traits

**Flyby.** The owl doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


---

### Actions

**Talons.** m +4, reach 5 ft. *Hit:* 7 (1d10 + 2) Slashing damage.


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