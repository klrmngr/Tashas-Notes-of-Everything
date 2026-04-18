---
type: pc
race: "Construct"
class:
 - "Shield Guardian"
subClass:
 - "CR 7"
cover: "Shield Guardian.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/7
  - source/xmm
---
###### Shield Guardian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Shield Guardian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 8 | 18 | 7 | 10 | 3 |
| **Mod** | +4 | -1 | +4 | -2 | +0 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 10
**Languages:** understands commands given in any language but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Bound.** The guardian is magically bound to an amulet. While the guardian and its amulet are on the same plane of existence, the amulet's wearer can telepathically call the guardian to travel to it, and the guardian knows the distance and direction to the amulet. If the guardian is within 60 feet of the amulet's wearer, half of any damage the wearer takes (round up) is transferred to the guardian.

**Regeneration.** The guardian regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.

**Spell Storing.** A spellcaster who wears the guardian's amulet can cause the guardian to store one spell of level 4 or lower. To do so, the wearer must cast the spell on the guardian while within 5 feet of it. The spell has no effect but is stored within the guardian. Any previously stored spell is lost when a new spell is stored. The guardian can cast the spell stored with any parameters set by the original caster, requiring no spell components and using the caster's spellcasting ability. The stored spell is then lost.


---

### Actions

**Multiattack.** The guardian makes two Fist attacks.

**Fist.** m +7, reach 10 ft. *Hit:* 11 (2d6 + 4) Bludgeoning damage plus 7 (2d6) Force damage.


---

### Reactions

**Protection.**  An attack roll hits the wearer of the guardian's amulet while the wearer is within 5 feet of the guardian.  The wearer gains a +5 bonus to AC, including against the triggering attack and possibly causing it to miss, until the start of the guardian's next turn.


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