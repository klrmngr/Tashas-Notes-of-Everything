---
type: pc
race: "Plant"
class:
 - "Astral Blight"
subClass:
 - "CR 1"
cover: "Astral Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1
  - source/lox
---
###### Astral Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LoX
___

> [!infobox|no-t right]
> ![[Astral Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | LoX |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 14 | 6 | 10 | 3 |
| **Mod** | +3 | -1 | +2 | -2 | +0 | -4 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Damage Resistances:** cold; radiant

---

### Traits

**Illumination.** While it has at least 1 hit point, the astral blight sheds dim light in a 10-foot radius.

**Unusual Nature.** The blight doesn't require air or sleep.


---

### Actions

**Multiattack.** The blight makes two Heat-Draining Vine attacks.

**Heat-Draining Vine.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 6 (1d6 + 3) radiant damage, and if the target is a Large or smaller creature, it is grappled (escape DC 13). Until this grapple ends, the target takes 3 (1d6) cold damage at the start of each of its turns. The blight has two vines, each of which can grapple one creature.


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