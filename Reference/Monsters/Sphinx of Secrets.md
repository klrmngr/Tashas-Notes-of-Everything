---
type: pc
race: "Celestial"
class:
 - "Sphinx of Secrets"
subClass:
 - "CR 8"
cover: "Sphinx of Secrets.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/8
  - source/xmm
---
###### Sphinx of Secrets
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sphinx of Secrets.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 18 | 18 | 18 |
| **Mod** | +4 | +2 | +3 | +4 | +4 | +4 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 17
**Languages:** Celestial, Common
**Skills:** History +7, Perception +7, Religion +7
**Damage Resistances:** necrotic; radiant
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Inscrutable.** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom (Insight) checks made to ascertain its intentions or sincerity are made with Disadvantage.

**Magic Resistance.** The sphinx has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The sphinx makes three Claw attacks. It can replace one attack with a use of Curse of the Riddle.

**Claw.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage plus 7 (2d6) Radiant damage.

**Curse of the Riddle.** int DC 15, one creature the sphinx can see within 60 feet.  21 (6d6) Psychic damage, and the target is cursed with a riddle. The cursed target has Disadvantage on ability checks and attack rolls. In addition, if it takes the Magic action, it must succeed on a DC 15 Intelligence saving throw or that action is wasted. The cursed target can take a Study action to make a DC 15 Intelligence check, solving the riddle and ending the curse on a success. The curse ends early if the sphinx curses another target.


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