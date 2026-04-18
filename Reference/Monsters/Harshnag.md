---
type: pc
race: "Giant"
class:
 - "Harshnag"
subClass:
 - "CR 9"
cover: "Harshnag.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/skt
---
###### Harshnag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Harshnag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 21 (+3 plate armor) |
> | :FasHeart: HP | 204 (12d12 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 21 | 9 | 10 | 12 |
| **Mod** | +6 | -1 | +5 | -1 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Giant
**Saving Throws:** Con +9, Wis +4, Cha +5
**Skills:** Athletics +10, Perception +4
**Damage Immunities:** cold

---

### Traits

**Legendary Resistance (1/Day).** If Harshnag fails a saving throw, he can choose to succeed instead.


---

### Actions

**Weighted Net.** Ranged Weapon Attack: +5 to hit, ranged 20/60 ft., one Small, Medium, or Large creature. *Hit:* The target is restrained until it escapes the net. Any creature can use its action to make a DC 17 Strength check to free itself or another creature in the net, ending the effect on a success. Dealing 15 slashing damage to the net (AC 12) destroys the net and frees the target.

**Multiattack.** The giant makes two greataxe attacks.

**Gurt's Greataxe.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 26 (3d12 + 7) slashing damage, or 39 (5d12 + 7) slashing damage if the target is human.

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