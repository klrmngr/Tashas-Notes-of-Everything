---
type: pc
race: "Humanoid (human)"
class:
 - "Burrowshark"
subClass:
 - "CR 4"
cover: "Burrowshark.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/pota
---
###### Burrowshark
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Burrowshark.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 10 | 11 | 13 |
| **Mod** | +4 | +1 | +3 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Animal Handling +2, Athletics +6, Intimidation +3, Perception +2

---

### Traits

**Bond of the Black Earth.** The burrowshark is magically bound to a bulette trained to serve as its mount. While mounted on its bulette, the burrowshark shares the bulette's senses and can ride the bulette while it burrows. The bonded bulette obeys the burrowshark's commands. If its mount dies, the burrowshark can train a new bulette to serve as its bonded mount, a process requiring a month.


---

### Actions

**Multiattack.** The burrowshark makes three melee attacks.

**Spear.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage if used with two hands to make a melee attack.


---

### Reactions

**Unyielding.** When the burrowshark is subjected to an effect that would move it, knock it prone, or both, it can use its reaction to be neither moved nor knocked prone.


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