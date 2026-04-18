---
type: pc
race: "Humanoid"
class:
 - "Pirate Captain"
subClass:
 - "CR 6"
cover: "Pirate Captain.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/xmm
---
###### Pirate Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pirate Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 14 | 10 | 14 | 17 |
| **Mod** | +0 | +4 | +2 | +0 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus one other language
**Saving Throws:** Str +3, Dex +7, Wis +5, Cha +6
**Skills:** Acrobatics +7, Perception +5

---

### Actions

**Multiattack.** The pirate makes three attacks, using Rapier or Pistol in any combination.

**Rapier.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Piercing damage, and the pirate has Advantage on the next attack roll it makes before the end of this turn.

**Pistol.** r +7, range 30/90 ft. *Hit:* 15 (2d10 + 4) Piercing damage.


---

### Bonus Actions

**Captain's Charm.** wis DC 14, one creature the pirate can see within 30 feet.  The target has the Charmed condition until the start of the pirate's next turn.


---

### Reactions

**Riposte.**  The pirate is hit by a melee attack roll while holding a weapon.  The pirate adds 3 to its AC against that attack, possibly causing it to miss. On a miss, the pirate makes one Rapier attack against the triggering creature if within range.


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