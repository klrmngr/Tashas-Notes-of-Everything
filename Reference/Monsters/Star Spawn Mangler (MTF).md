---
type: pc
race: "Aberration"
class:
 - "Star Spawn Mangler"
subClass:
 - "CR 5"
cover: "Star Spawn Mangler.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/mtf
---
###### Star Spawn Mangler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Star Spawn Mangler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 18 | 12 | 11 | 12 | 7 |
| **Mod** | -1 | +4 | +1 | +0 | +1 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Deep Speech
**Saving Throws:** Dex +7, Con +4
**Skills:** Stealth +7
**Damage Resistances:** cold
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened; prone

---

### Traits

**Ambusher.** On the first round of each combat, the mangler has advantage on attack rolls against a creature that hasn't taken a turn yet.

**Shadow Stealth.** While in dim light or darkness, the mangler can take the Hide action as a bonus action.


---

### Actions

**Multiattack.** The mangler makes two claw attacks.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage. If the attack roll has advantage, the target also takes 7 (2d6) psychic damage.

**Flurry of Claws (Recharge 4–6).** The mangler makes six claw attacks against one target. Either before or after these attacks, it can move up to its speed as a bonus action without provoking opportunity attacks.


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