---
type: pc
race: "Fey"
class:
 - "Dire Worg"
subClass:
 - "CR 10"
cover: "Dire Worg.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/huge
  - cr/10
  - source/xmm
---
###### Dire Worg
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dire Worg.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Fey |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 147 (14d12 + 56) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 14 | 18 | 7 | 16 | 8 |
| **Mod** | +6 | +2 | +4 | -2 | +3 | -1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 21
**Languages:** Goblin, Sylvan, Worg
**Saving Throws:** Dex +6, Wis +7
**Skills:** Perception +11

---

### Traits

**Magic Resistance.** The worg has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The worg makes three Bite attacks.

**Bite.** m +10, reach 5 ft. *Hit:* 15 (2d8 + 6) Piercing damage plus 7 (2d6) Poison damage, and the target has the Poisoned condition until the start of the worg's next turn. While Poisoned, the target can't regain Hit Points.

**Dreadful Howl (Recharge 5–6).** wis DC 16, each creature within 30 feet that isn't a worg.  36 (8d8) Psychic damage, and the target has the Frightened condition until the start of the worg's next turn.  Half damage only.


---

### Bonus Actions

**Warp Step.** The worg teleports, along with a willing creature of its choice within 5 feet of it, up to 30 feet to an unoccupied space it can see.


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