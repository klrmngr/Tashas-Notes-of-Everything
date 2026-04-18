---
type: pc
race: "Celestial"
class:
 - "Sphinx of Valor"
subClass:
 - "CR 17"
cover: "Sphinx of Valor.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/17
  - source/xmm
---
###### Sphinx of Valor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sphinx of Valor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 199 (19d10 + 95) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 20 | 16 | 23 | 18 |
| **Mod** | +6 | +0 | +5 | +3 | +6 | +4 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 22
**Languages:** Celestial, Common
**Saving Throws:** Dex +6, Con +11, Int +9, Wis +12
**Skills:** Arcana +9, Perception +12, Religion +15
**Damage Resistances:** necrotic; radiant
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Inscrutable.** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom (Insight) checks made to ascertain its intentions or sincerity are made with Disadvantage.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the sphinx fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The sphinx makes two Claw attacks and uses Roar.

**Claw.** m +12, reach 5 ft. *Hit:* 20 (4d6 + 6) Slashing damage.

**Roar (3/Day).** The sphinx emits a magical roar. Whenever it roars, the roar has a different effect, as detailed below (the sequence resets when it takes a Long Rest):
- **First Roar.** wis DC 20, each enemy in a 500-foot Emanation originating from the sphinx.  The target has the Frightened condition for 1 minute.
- **Second Roar.** wis DC 20, each enemy in a 500-foot Emanation originating from the sphinx.  The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- **Third Roar.** con DC 20, each enemy in a 500-foot Emanation originating from the sphinx.  44 (8d10) Thunder damage, and the target has the Prone condition.  Half damage only.


---

### Legendary Actions

### 

**Arcane Prowl.** The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.

**Weight of Years.** con DC 16, one creature the sphinx can see within 120 feet.  The target gains 1 Exhaustion level. While the target has any Exhaustion levels, it appears 3d10 years older.  The sphinx can't take this action again until the start of its next turn.


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