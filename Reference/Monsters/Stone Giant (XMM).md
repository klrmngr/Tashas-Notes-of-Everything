---
type: pc
race: "Giant"
class:
 - "Stone Giant"
subClass:
 - "CR 7"
cover: "Stone Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/7
  - source/xmm
---
###### Stone Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Stone Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 20 | 10 | 12 | 9 |
| **Mod** | +6 | +2 | +5 | +0 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Giant
**Saving Throws:** Dex +5, Con +8, Wis +4
**Skills:** Athletics +12, Perception +4, Stealth +5

---

### Actions

**Multiattack.** The giant makes two attacks, using Stone Club or Boulder in any combination.

**Stone Club.** m +9, reach 15 ft. *Hit:* 22 (3d10 + 6) Bludgeoning damage.

**Boulder.** r +9, range 60/240 ft. *Hit:* 15 (2d8 + 6) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.


---

### Reactions

**Deflect Missile (Recharge 5–6).**  The giant is hit by a ranged attack roll and takes Bludgeoning, Piercing, or Slashing damage from it.  The giant reduces the damage it takes from the attack by 11 (1d10 + 6), and if that damage is reduced to 0, the giant can redirect some of the attack's force. dex DC 17, one creature the giant can see within 60 feet.  11 (1d10 + 6) Force damage.


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