---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Favored Consort"
subClass:
 - "CR 18"
cover: "Drow Favored Consort.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/18
  - source/mtf
---
###### Drow Favored Consort
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Drow Favored Consort.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15; 18 with mage armor |
> | :FasHeart: HP | 225 (30d8 + 90) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 20 | 16 | 18 | 15 | 18 |
| **Mod** | +2 | +5 | +3 | +4 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Elvish, Undercommon
**Saving Throws:** Dex +11, Con +9, Cha +10
**Skills:** Acrobatics +11, Athletics +8, Perception +8, Stealth +11

---

### Traits

**Fey Ancestry.** The drow has advantage on saving throws against being charmed, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**War Magic.** When the drow uses its action to cast a spell, it can make one weapon attack as a bonus action.


---

### Actions

**Multiattack.** The drow makes three scimitar attacks.

**Scimitar.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage plus 18 (4d8) poison damage. In addition, the target has disadvantage on the next saving throw it makes against a spell the drow casts before the end of the drow's next turn.

**Hand Crossbow.** Ranged Weapon Attack: +11 to hit, range 30/120 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned for 1 hour. If the saving throw fails by 5 or more, the target is also unconscious while poisoned in this way. The target regains consciousness if it takes damage or if another creature takes an action to shake it.


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