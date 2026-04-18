---
type: pc
race: "Construct"
class:
 - "Helmed Horror"
subClass:
 - "CR 4"
cover: "Helmed Horror.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/xmm
---
###### Helmed Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Helmed Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 10 | 10 | 10 |
| **Mod** | +4 | +1 | +3 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 14
**Languages:** understands Common plus one other language but can't speak
**Skills:** Perception +4
**Damage Immunities:** necrotic; poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Magic Resistance.** The helmed horror has Advantage on saving throws against spells and other magical effects.

**Spell Immunity.** The helmed horror is immune to three spells chosen by its creator. Typical choices include Heat Metal, Lightning Bolt, and Magic Missile.


---

### Actions

**Multiattack.** The helmed horror makes two Arcane Sword attacks.

**Arcane Sword.** m +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Slashing damage plus 5 (1d10) Force damage.


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