---
type: pc
race: "Humanoid (orc)"
class:
 - "Orc Red Fang of Shargaas"
subClass:
 - "CR 3"
cover: "Orc Red Fang of Shargaas.png"
campaign:
locations:
tags:
  - race/orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/vgm
---
###### Orc Red Fang of Shargaas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Orc Red Fang of Shargaas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (orc) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 15 | 9 | 11 | 9 |
| **Mod** | +0 | +3 | +2 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Orc
**Skills:** Intimidation +1, Perception +2, Stealth +5

---

### Traits

**Cunning Action.** On each of its turns, the orc can use a bonus action to take the Dash, Disengage, or Hide action.

**Hand of Shargaas.** The orc deals 2 extra dice of damage when it hits a target with a weapon attack (included in its attacks).

**Shargaas's Sight.** Magical darkness doesn't impede the orc's darkvision.

**Slayer.** In the first round of a combat, the orc has advantage on attack rolls against any creature that hasn't taken a turn yet. If the orc hits a creature that round who was surprised, the hit is automatically a critical hit.


---

### Actions

**Multiattack.** The orc makes two scimitar or dart attacks.

**Scimitar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 13 (3d6 + 3) slashing damage.

**Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 10 (3d4 + 3) piercing damage.

**Veil of Shargaas (Recharges after a Short or Long Rest).** The orc casts darkness without any components. Wisdom is its spellcasting ability.


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