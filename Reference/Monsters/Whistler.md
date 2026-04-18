---
type: pc
race: "Aberration"
class:
 - "Whistler"
subClass:
 - "CR 9"
cover: "Whistler.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/9
  - source/jttrc
---
###### Whistler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Whistler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 180 (24d10 + 48) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 14 | 15 | 16 | 18 |
| **Mod** | +1 | +3 | +2 | +2 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Dex +7, Cha +8
**Skills:** Stealth +11
**Damage Resistances:** psychic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Blurred Form.** Attack rolls against the whistler are made with disadvantage unless the whistler is incapacitated.

**Unusual Nature.** The whistler doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The whistler makes three Psychic Swipe attacks.

**Psychic Swipe.** Melee Spell Attack: +8 to hit, reach 10 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage.

**Otherworldly Melody (Recharge 5–6).** The whistler telepathically whistles an otherworldly melody into the minds of up to two creatures it can see within range of its telepathy. Each target must succeed on a DC 16 Wisdom saving throw or take 33 (6d10) psychic damage and become frightened of the whistler for 1 minute. A frightened creature can repeat this saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Surreal Step.** The whistler teleports up to 20 feet to an unoccupied space it can see.


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