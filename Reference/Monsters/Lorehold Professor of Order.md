---
type: pc
race: "Humanoid (wizard)"
class:
 - "Lorehold Professor of Order"
subClass:
 - "CR 7"
cover: "Lorehold Professor of Order.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Lorehold Professor of Order
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Lorehold Professor of Order.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 19 | 15 | 13 |
| **Mod** | +0 | +2 | +2 | +4 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus any four languages
**Saving Throws:** Con +5, Int +7, Wis +5, Cha +4
**Skills:** Arcana +7, History +7, Perception +5
**Damage Resistances:** force

---

### Traits

**Voice from the Past (1/Day).** The professor can cast the contact other plane spell to contact a long-dead spirit, using Intelligence as the spellcasting ability.


---

### Actions

**Multiattack.** The professor makes two Repelling Burst attacks. It can also use Force Barrier, if available.

**Repelling Burst.** Melee Spell Attack: +7 to hit, reach 30 ft., one target. *Hit:* 13 (2d8 + 4) force damage. If the target is a Large or smaller creature, it must succeed on a DC 15 Strength saving throw or be pushed up to 10 feet directly away from the professor and become restrained until the start of professor's next turn.

**Force Barrier (Recharge 5–6).** The professor magically creates a wall of translucent, golden force within 90 feet of itself. The wall lasts for 1 minute or until the professor uses this action again. The barrier can be a vertical or horizontal plane up to 30 feet on a side or a 10-foot-radius hemispherical dome with a floor. The wall provides 3. It has AC 17, 30 hit points, and immunity to poison and psychic damage.


---

### Reactions

**Arcane Stasis (2/Day).** When a creature the professor can see within 60 feet of it casts a spell, the professor can magically lock the casting in the moment before completion. The spellcaster must succeed on a DC 15 saving throw using the spell's spellcasting ability, or the spell fails and is wasted.


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