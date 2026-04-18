---
type: pc
race: "Giant"
class:
 - "Guardian Giant"
subClass:
 - "CR 8"
cover: "Guardian Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/ggr
---
###### Guardian Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Guardian Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 19 (half plate armor, shield) |
> | :FasHeart: HP | 137 (11d12 + 66) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 17 | 22 | 10 | 18 | 12 |
| **Mod** | +7 | +3 | +6 | +0 | +4 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Common, Giant
**Saving Throws:** Dex +6, Wis +7
**Skills:** Insight +7, Perception +10

---

### Traits

**Vigilant.** The giant can't be surprised.


---

### Actions

**Multiattack.** The giant makes three spear attacks.

**Spear.** Melee or Ranged Weapon Attack: +10 to hit, reach 10 ft. or range 60/240 ft., one target. *Hit:* 17 (3d6 + 7) piercing damage, or 20 (3d8 + 7) piercing damage if used with two hands to make a melee attack.


---

### Reactions

**Protection.** When an attacker the giant can see makes an attack roll against a creature within 10 feet of the giant, the giant can impose disadvantage on the attack roll.


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