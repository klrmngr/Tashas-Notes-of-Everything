---
type: pc
race: "Undead"
class:
 - "Eldritch Lich"
subClass:
 - "CR 15"
cover: "Eldritch Lich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/15
  - source/mcv1sc
---
###### Eldritch Lich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Eldritch Lich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 165 (22d8 + 66) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 16 | 19 | 14 | 12 |
| **Mod** | +0 | +4 | +3 | +4 | +2 | +1 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120ft., passive Perception 17
**Languages:** Common, Deep Speech, telepathy 120 ft.
**Saving Throws:** Int +9, Wis +7
**Skills:** Arcana +14, Perception +7
**Damage Resistances:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Far Realm Parasite.** Inside the lich's torso dwells a wormlike parasite that contains the lich's soul. When the lich dies, it implodes into the parasite, which then vanishes into the Far Realm. In 2d4 days, the parasite causes the lich to reappear within 1d4 miles of where it died. If the lich died inside a magic circle cast to contain Undead, the lich instead reappears as an [[Otyugh]] with all the lich's memories.

**Legendary Resistance (4/Day).** If the lich fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The lich doesn't need air, food, drink, or sleep.


---

### Actions

**Multiattack.** The lich makes one Parasitic Tentacle attack or uses Spellcasting. The lich also uses Psychic Whisper twice.

**Parasitic Tentacle.** Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. *Hit:* 25 (6d6 + 4) piercing damage plus 25 (6d6 + 4) necrotic damage. The target must succeed on a DC 17 Constitution saving throw or be poisoned. The poisoned target can repeat the save at the end of each of its turns, ending the effect on itself on a success. The third time the target fails the save, the target dies and dissolves into a [[Gibbering Mouther]] that obeys the lich and uses the target's initiative.

**Psychic Whisper.** The lich targets one creature it can see within 120 feet of itself. The target must succeed on a DC 17 Wisdom saving throw or take 25 (6d6 + 4) psychic damage and be stunned until the end of the lich's next turn as incomprehensible whispers fill the target's mind.


---

### Reactions

**Far Realm Step.** Immediately after taking damage, the lich, along with any equipment it is wearing or carrying, magically teleports up to 60 feet to an unoccupied space it can see.


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