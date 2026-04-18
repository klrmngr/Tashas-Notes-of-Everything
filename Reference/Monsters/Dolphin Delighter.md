---
type: pc
race: "Fey"
class:
 - "Dolphin Delighter"
subClass:
 - "CR 3"
cover: "Dolphin Delighter.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/mpmm
---
###### Dolphin Delighter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Dolphin Delighter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 13 | 11 | 12 | 16 |
| **Mod** | +2 | +1 | +1 | +0 | +1 | +3 |

**Speed:** 0 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** Aquan, telepathy 120 ft.
**Saving Throws:** Wis +3, Cha +5
**Skills:** Perception +3, Performance +5

---

### Traits

**Hold Breath.** The dolphin can hold its breath for 20 minutes.


---

### Actions

**Multiattack.** The dolphin makes two Dazzling Slam attacks.

**Dazzling Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage plus 7 (2d6) psychic damage, and the target is blinded until the start of the dolphin's next turn.


---

### Bonus Actions

**Delightful Light (Recharge 5–6).** The dolphin magically emanates light in a 10-foot radius for a moment. The dolphin and each creature of its choice in that light gain 11 (2d10) temporary hit points.

**Fey Leap.** The dolphin teleports up to 30 feet to an unoccupied space it can see. Immediately before teleporting, the dolphin can choose one creature within 5 feet of it. That creature can teleport with the dolphin, appearing in an unoccupied space within 5 feet of the dolphin's destination space.


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