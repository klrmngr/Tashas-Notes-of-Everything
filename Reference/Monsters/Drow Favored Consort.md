---
type: pc
race: "Humanoid (elf, wizard)"
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
  - source/mpmm
---
###### Drow Favored Consort
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Drow Favored Consort.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 240 (32d8 + 96) |
> | :FasUserGroup: Race | Humanoid (elf, wizard) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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


---

### Actions

**Multiattack.** The drow makes three Scimitar or Arcane Eruption attacks. The drow can replace one of the attacks with a use of Spellcasting.

**Scimitar.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage plus 27 (6d8) poison damage.

**Arcane Eruption.** Ranged Spell Attack: +10 to hit, range 120 ft., one target. *Hit:* 36 (8d8) force damage, and the drow can push the target up to 10 feet away if it is a Large or smaller creature.


---

### Reactions

**Protective Shield (3/Day).** When the drow or a creature within 10 feet of it is hit by an attack roll, the drow gives the target a +5 bonus to its AC until the start of the drow's next turn, which can cause the triggering attack roll to miss.


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