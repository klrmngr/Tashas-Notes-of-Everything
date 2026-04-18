---
type: pc
race: "Dragon"
class:
 - "Half-Dragon"
subClass:
 - "CR 5"
cover: "Half-Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/5
  - source/xmm
---
###### Half-Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Half-Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 16 | 10 | 15 | 14 |
| **Mod** | +4 | +2 | +3 | +0 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 15
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +5
**Skills:** Athletics +7, Perception +5, Stealth +5

---

### Traits

**Draconic Origin.** The half-dragon is related to a type of dragon associated with one of the following damage types (DM's choice): Acid, Cold, Fire, Lightning, or Poison. This choice affects other aspects of the stat block.


---

### Actions

**Multiattack.** The half-dragon makes two Claw attacks.

**Claw.** m +7, reach 10 ft. *Hit:* 6 (1d4 + 4) Slashing damage plus 7 (2d6) damage of the type chosen for the Draconic Origin trait.

**Dragon's Breath (Recharge 5–6).** dex DC 14, each creature in a 30-foot Cone.  28 (8d6) damage of the type chosen for the Draconic Origin trait.  Half damage.


---

### Bonus Actions

**Leap.** The half-dragon jumps up to 30 feet by spending 10 feet of movement.


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