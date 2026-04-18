---
type: pc
race: "Humanoid (minotaur, warlock)"
class:
 - "Brusipha"
subClass:
 - "CR 3"
cover: "Brusipha.png"
campaign:
locations:
tags:
  - race/minotaur
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bmt
---
###### Brusipha
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Brusipha.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (minotaur, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Humanoid (minotaur, warlock) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 12 | 16 | 16 |
| **Mod** | +4 | +0 | +3 | +1 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, Common
**Saving Throws:** Wis +5, Cha +5
**Skills:** Deception +5, Perception +7, Religion +3

---

### Traits

**Demonic Ritual.** Brusipha can spend 3 hours performing a ritual that summons 1d3 + 1 barlguras or 1 hezrou. She must sacrifice a Medium or larger living creature to Baphomet during this ritual, and the ritual can be performed only at night. The demons vanish at dawn.

**Labyrinthine Recall.** Brusipha can perfectly recall any path she has traveled.


---

### Actions

**Multiattack.** Brusipha makes two Eldritch Blast attacks.

**Eldritch Blast.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 8 (1d10 + 3) force damage.

**Gore.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage plus 4 (1d8) necrotic damage. If Brusipha moved at least 10 feet straight toward the target immediately before she hit, the target takes an extra 4 (1d8) piercing damage, and if the target is a creature, it must succeed on a DC 15 Strength saving throw or be pushed up to 10 feet from Brusipha and have the prone condition.

**Incite the Hunters (Recharges after a Short or Long Rest).** Brusipha allows each ally within 30 feet of herself that has the Unerring Tracker trait to make one weapon attack as a reaction against the target of that ally's Unerring Tracker.


---

### Bonus Actions

**Unerring Tracker.** Brusipha magically creates a psychic link with one creature she can see. For the next hour, Brusipha knows the current distance and direction to the target if it is on the same plane of existence. The link ends if Brusipha has the incapacitated condition or uses this ability on a different target.


---

### Reactions

**Baphomet's Blessing.** When Brusipha reduces a hostile creature to 0 hit points, she gains 8 temporary hit points.


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