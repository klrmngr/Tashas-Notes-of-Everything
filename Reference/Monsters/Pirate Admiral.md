---
type: pc
race: "Humanoid"
class:
 - "Pirate Admiral"
subClass:
 - "CR 12"
cover: "Pirate Admiral.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/12
  - source/xmm
---
###### Pirate Admiral
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pirate Admiral.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 182 (28d8 + 56) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 22 | 14 | 12 | 14 | 19 |
| **Mod** | +2 | +6 | +2 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus one other language
**Saving Throws:** Str +6, Dex +10, Wis +6, Cha +8
**Skills:** Acrobatics +10, Athletics +6, Perception +6

---

### Actions

**Multiattack.** The pirate makes three attacks, using Scimitar or Pistol in any combination.

**Scimitar.** m +10, reach 5 ft. *Hit:* 16 (3d6 + 6) Slashing damage plus 7 (2d6) Poison damage, and the target suffers one of the following effects of the pirate's choice:
- **Awestruck.** The target has the Charmed condition until the start of the pirate's next turn.
- **Poison.** The target has the Poisoned condition until the start of the pirate's next turn.

**Pistol.** r +10, range 30/90 ft. *Hit:* 28 (4d10 + 6) Piercing damage.


---

### Bonus Actions

**Rally (1/Day).** The pirate chooses up to three other creatures it can see within 30 feet. Until the start of the pirate's next turn, the targets have Advantage on attack rolls and saving throws.


---

### Reactions

**Defensive Stance.**  The pirate is hit by a melee attack roll while holding a weapon.  The pirate adds 4 to its AC against melee attack rolls (including the triggering attack) until the start of its next turn, possibly causing the attacks to miss.


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