---
type: pc
race: "Elemental"
class:
 - "Elemental Spirit"
subClass:
 - "CR —"
cover: "Elemental Spirit.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/—
  - source/xphb
---
###### Elemental Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Elemental Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 50 + 10 for each spell level above 4 |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 17 | 4 | 10 | 16 |
| **Mod** | +4 | +2 | +3 | -3 | +0 | +3 |

**Speed:** 40 ft., burrow 40 ft. ((Earth only)), fly 40 ft. ((hover; Air only)) (hover), swim 40 ft. ((Water only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial, understands the languages you know
**Damage Resistances:** lightning, thunder (Air only); piercing, slashing (Earth only); acid (Water only)
**Damage Immunities:** poison; fire (Fire only)
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Amorphous Form (Air, Fire, and Water Only).** The spirit can move through a space as narrow as 1 inch wide without it counting as Difficult Terrain.


---

### Actions

**Multiattack.** The spirit makes a number of Slam attacks equal to half this spell's level (round down).

**Slam.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d10 + 4 + summonSpellLevel Bludgeoning (Earth only), Cold (Water only), Lightning (Air only), or Fire (Fire only) damage.


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