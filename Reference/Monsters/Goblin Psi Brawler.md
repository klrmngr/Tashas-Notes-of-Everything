---
type: pc
race: "Aberration (goblinoid)"
class:
 - "Goblin Psi Brawler"
subClass:
 - "CR 2"
cover: "Goblin Psi Brawler.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/2
  - source/pabtso
---
###### Goblin Psi Brawler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Goblin Psi Brawler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Aberration (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (studded leather armor) |
> | :FasHeart: HP | 31 (7d6 + 7) |
> | :FasUserGroup: Race | Aberration (goblinoid) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 17 | 12 | 16 | 15 | 10 |
| **Mod** | -1 | +3 | +1 | +3 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Goblin, telepathy 30 ft.
**Saving Throws:** Int +5, Wis +4
**Skills:** Stealth +7
**Damage Resistances:** psychic

---

### Traits

**Mental Burst.** When the goblin dies, its pent-up mental energy explodes in a psychic blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence saving throw or take 5 (2d4) psychic damage.

**Mental Fortitude.** The goblin has advantage on saving throws against effects that would make it have the charmed or frightened condition.


---

### Actions

**Multiattack.** The goblin makes two Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage plus 3 (1d6) psychic damage.


---

### Bonus Actions

**Nimble Escape.** The goblin takes the Disengage or Hide action.

**Telekinetic Shove.** The goblin targets one creature it can see within 30 feet of itself with a thrust of telekinetic force. The target must succeed on a DC 13 Strength saving throw or have the prone condition.


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