---
type: pc
race: "Humanoid"
class:
 - "Bandit Captain"
subClass:
 - "CR 2"
cover: "Bandit Captain.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/xmm
---
###### Bandit Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bandit Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 14 | 14 | 11 | 14 |
| **Mod** | +2 | +3 | +2 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Thieves' cant
**Saving Throws:** Str +4, Dex +5, Wis +2
**Skills:** Athletics +4, Deception +4

---

### Actions

**Multiattack.** The bandit makes two attacks, using Scimitar and Pistol in any combination.

**Scimitar.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage.

**Pistol.** r +5, range 30/90 ft. *Hit:* 8 (1d10 + 3) Piercing damage.


---

### Reactions

**Parry.**  The bandit is hit by a melee attack roll while holding a weapon.  The bandit adds 2 to its AC against that attack, possibly causing it to miss.


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