---
type: pc
race: "Fiend (devil)"
class:
 - "Speaker Devil"
subClass:
 - "CR 12"
cover: "Speaker Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/12
  - source/abh
---
###### Speaker Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: ABH
___

> [!infobox|no-t right]
> ![[Speaker Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | ABH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 19 | 20 | 22 | 18 | 17 |
| **Mod** | +5 | +4 | +5 | +6 | +4 | +3 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 18
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Con +9, Int +10, Wis +8, Cha +7
**Skills:** Arcana +10, History +10, Perception +8
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes two Thundering Halberd attacks.

**Thundering Halberd.** m +9, reach 10 ft. *Hit:* 16 (2d10 + 5) Slashing damage plus 14 (4d6) Thunder damage.


---

### Bonus Actions

**Utterance of Pain.** wis DC 18, each creature in a 20-foot Emanation originating from the devil.  The target has the Stunned condition until the end of the devil's next turn.

**Utterance of Unmaking.** con DC 18, each creature in a 20-foot Emanation originating from the devil.  22 (4d10) Force damage.  Half damage.


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