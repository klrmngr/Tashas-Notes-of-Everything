---
type: pc
race: "Construct"
class:
 - "Bronze Sable"
subClass:
 - "CR 1"
cover: "Bronze Sable.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/mot
---
###### Bronze Sable
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Bronze Sable.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 3 | 14 | 1 |
| **Mod** | +1 | +3 | +2 | -4 | +2 | -5 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** understands one language of its creator but can't speak
**Skills:** Stealth +5
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** While the sable remains motionless, it is indistinguishable from a normal statue.

**Pack Tactics.** The sable has advantage on an attack roll against a creature if at least one of the sable's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Surprise Attack.** If the sable surprises a creature and hits it with an attack during the first round of combat, the target takes an extra 10 (3d6) damage from the attack.


---

### Actions

**Multiattack.** The sable makes two bite attacks.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


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