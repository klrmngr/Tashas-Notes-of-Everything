---
type: pc
race: "Undead"
class:
 - "Mummy"
subClass:
 - "CR 3"
cover: "Mummy.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/3
  - source/xmm
---
###### Mummy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mummy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 15 | 6 | 12 | 12 |
| **Mod** | +3 | -1 | +2 | -2 | +1 | +1 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common plus two other languages
**Saving Throws:** Wis +3
**Damage Vulnerabilities:** fire
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Actions

**Multiattack.** The mummy makes two Rotting Fist attacks and uses Dreadful Glare.

**Rotting Fist.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain Hit Points, its Hit Point maximum doesn't return to normal when finishing a Long Rest, and its Hit Point maximum decreases by 10 (3d6) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 Hit Points by this attack.

**Dreadful Glare.** wis DC 11, one creature the mummy can see within 60 feet.  The target has the Frightened condition until the end of the mummy's next turn.  The target is immune to this mummy's Dreadful Glare for 24 hours.


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