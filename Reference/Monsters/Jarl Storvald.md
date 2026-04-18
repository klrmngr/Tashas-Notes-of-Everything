---
type: pc
race: "Giant"
class:
 - "Jarl Storvald"
subClass:
 - "CR 8"
cover: "Jarl Storvald.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/skt
---
###### Jarl Storvald
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Jarl Storvald.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (barding scraps) |
> | :FasHeart: HP | 189 (12d12 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 21 | 9 | 16 | 16 |
| **Mod** | +6 | -1 | +5 | -1 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Giant, Giant Owl
**Saving Throws:** Con +8, Wis +6, Cha +6
**Skills:** Athletics +9, Perception +6
**Damage Immunities:** cold

---

### Actions

**Weighted Net.** Ranged Weapon Attack: +5 to hit, ranged 20/60 ft., one Small, Medium, or Large creature. *Hit:* The target is restrained until it escapes the net. Any creature can use its action to make a DC 17 Strength check to free itself or another creature in the net, ending the effect on a success. Dealing 15 slashing damage to the net (AC 12) destroys the net and frees the target.

**Multiattack.** The giant makes two greataxe attacks.

**Greataxe.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 25 (3d12 + 6) slashing damage.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage.


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