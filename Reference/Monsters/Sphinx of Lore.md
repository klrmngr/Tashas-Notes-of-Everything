---
type: pc
race: "Celestial"
class:
 - "Sphinx of Lore"
subClass:
 - "CR 11"
cover: "Sphinx of Lore.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/11
  - source/xmm
---
###### Sphinx of Lore
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sphinx of Lore.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 170 (20d10 + 60) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 18 | 18 | 18 |
| **Mod** | +4 | +2 | +3 | +4 | +4 | +4 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 18
**Languages:** Celestial, Common
**Skills:** Arcana +12, History +12, Perception +8, Religion +12
**Damage Resistances:** necrotic; radiant
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Inscrutable.** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom (Insight) checks made to ascertain its intentions or sincerity are made with Disadvantage.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the sphinx fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The sphinx makes three Claw attacks.

**Claw.** m +8, reach 5 ft. *Hit:* 14 (3d6 + 4) Slashing damage.

**Mind-Rending Roar (Recharge 5–6).** wis DC 16, each enemy in a 300-foot Emanation originating from the sphinx.  35 (10d6) Psychic damage, and the target has the Incapacitated condition until the start of the sphinx's next turn.


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