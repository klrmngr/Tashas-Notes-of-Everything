---
type: pc
race: "Dragon (chromatic)"
class:
 - "Young White Dragon"
subClass:
 - "CR 6"
cover: "Young White Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/6
  - source/xmm
---
###### Young White Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young White Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Dragon (chromatic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 18 | 6 | 11 | 12 |
| **Mod** | +4 | +0 | +4 | -2 | +0 | +1 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 16
**Languages:** Common, Draconic
**Saving Throws:** Dex +3, Wis +3
**Skills:** Perception +6, Stealth +3
**Damage Immunities:** cold

---

### Traits

**Ice Walk.** The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +7, reach 10 ft. *Hit:* 9 (2d4 + 4) Slashing damage plus 2 (1d4) Cold damage.

**Cold Breath (Recharge 5–6).** con DC 15, each creature in a 30-foot Cone.  40 (9d8) Cold damage.  Half damage.


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