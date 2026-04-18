---
type: pc
race: "Monstrosity"
class:
 - "Marlos Urnrayle"
subClass:
 - "CR 8"
cover: "Marlos Urnrayle.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/8
  - source/pota
---
###### Marlos Urnrayle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Marlos Urnrayle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 11 | 18 | 12 | 13 | 17 |
| **Mod** | +3 | +0 | +4 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 14
**Languages:** Common, Terran
**Skills:** Arcana +4, Deception +6, Perception +4
**Damage Resistances:** acid

---

### Traits

**Earthen Defeat.** When Marlos drops to 0 hit points, his body transforms into mud and collapses into a pool. Anything he is wearing or carrying is left behind.

**Earth Passage.** Marlos can move in 3 composed of anything made from earth or stone as if it were normal terrain. He can move through solid earth and rock as if it were 3. If he ends his turn there, he is shunted into the nearest space he last occupied.

**Legendary Resistance (2/Day).** If Marlos fails a saving throw, he can choose to succeed instead.

**Petrifying Gaze.** When a creature that can see Marlos's eyes starts its turn within 30 feet of him, Marlos can force it to make a DC 14 Constitution saving throw if Marlos isn't incapacitated and can see the creature. If the saving throw fails by 5 or more, the creature is instantly petrified. Otherwise, a creature that fails the save begins to turn to stone and is restrained. The restrained creature must repeat the saving throw at the end of its next turn, becoming petrified on a failure or ending the effect on a success. The petrification lasts until the creature is freed by the greater restoration spell or other magic.
Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see Marlos until the start of its next turn, when it can decide to avert its eyes again. If the creature looks at Marlos in the meantime, it must immediately make the save.
If Marlos sees himself reflected on a polished surface within 30 feet of him and in an area of bright light, Marlos is, due to his curse, affected by his own gaze.


---

### Actions

**Multiattack.** Marlos makes three melee attacks, one with his snake hair and two with Ironfang.

**Snake Hair.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 14 (4d6) poison damage.

**Ironfang.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 4 (1d8) thunder damage.


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