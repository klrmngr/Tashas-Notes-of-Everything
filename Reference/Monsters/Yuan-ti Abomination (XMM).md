---
type: pc
race: "Monstrosity"
class:
 - "Yuan-ti Abomination"
subClass:
 - "CR 7"
cover: "Yuan-ti Abomination.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/7
  - source/xmm
---
###### Yuan-ti Abomination
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Yuan-ti Abomination.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 17 | 17 | 18 | 15 |
| **Mod** | +4 | +3 | +3 | +3 | +4 | +2 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, Common, Draconic
**Skills:** Perception +7, Stealth +6
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The yuan-ti has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yuan-ti makes two Bite attacks, and it can use Spellcasting to cast Suggestion if available.

**Bite.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage plus 10 (3d6) Poison damage.

**Constrict.** str DC 15, one Large or smaller creature within 5 feet.  28 (7d6 + 4) Bludgeoning damage. The target has the Grappled condition (escape DC 14), and it has the Restrained condition until the grapple ends.  Half damage only.

**Poison Spray (Recharge 5–6).** con DC 14, each creature in a 30-foot Cone.  21 (6d6) Poison damage, and the target has the Poisoned condition until the end of the yuan-ti's next turn. While Poisoned, the target has the Blinded condition.  Half damage only.


---

### Bonus Actions

**Shape-Shift.** The yuan-ti shape-shifts into a Large snake or returns to its true form. If it dies, it stays in its current form. The yuan-ti's game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.


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