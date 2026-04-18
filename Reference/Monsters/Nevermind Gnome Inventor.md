---
type: pc
race: "Humanoid"
class:
 - "Nevermind Gnome Inventor"
subClass:
 - "CR 2"
cover: "Nevermind Gnome Inventor.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/mcv2dc
---
###### Nevermind Gnome Inventor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Nevermind Gnome Inventor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 36 (8d6 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 13 | 18 | 11 | 14 |
| **Mod** | -1 | +3 | +1 | +4 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Gnomish
**Saving Throws:** Dex +5, Int +6
**Skills:** Arcana +6, Investigation +6, Perception +2

---

### Traits

**Always Thinking Ahead.** The inventor has advantage on initiative rolls.


---

### Actions

**Multiattack.** The inventor makes two Flying Fangtrap attacks. It can replace one of these attacks with Thunderscream Gadget if it's available.

**Flying Fangtrap.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage, and the creature must succeed on a DC 14 Dexterity saving throw or have its speed reduced to 0 until the start of the inventor's next turn.

**Thunderscream Gadget (Recharge 5–6).** The inventor produces a gadget that emits a screeching wave of sound in a 30-foot cone originating from the inventor. Each creature in that area must make a DC 14 Constitution saving throw, taking 10 (3d6) thunder damage on a failed save or half as much damage on a successful one.


---

### Reactions

**Flash Powder.** If the inventor is damaged by a creature it can see within 15 feet of itself, the inventor retaliates by flinging brilliantly explosive powder at the creature. The creature must succeed on a DC 14 Dexterity saving throw or be blinded until the end of its next turn.


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