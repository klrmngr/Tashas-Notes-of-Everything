---
type: pc
race: "Celestial"
class:
 - "Veiled Presence"
subClass:
 - "CR 21"
cover: "Veiled Presence.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/small
  - cr/21
  - source/bmt
---
###### Veiled Presence
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Veiled Presence.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Small Celestial |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 300 (40d8 + 120) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 24 | 16 | 24 | 20 | 22 |
| **Mod** | +2 | +7 | +3 | +7 | +5 | +6 |

**Speed:** 40 ft., fly 80 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 22
**Languages:** all
**Saving Throws:** Dex +14, Int +14
**Skills:** Perception +12, Stealth +21
**Damage Resistances:** necrotic; radiant
**Condition Immunities:** charmed; frightened

---

### Traits

**Inviolate Presence.** The veiled presence can't be targeted by divination magic or by features that would read its mind or determine its creature type.

**Legendary Resistance (3/Day).** If the veiled presence fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The veiled presence makes two Blade of Judgment attacks and can use Revelation.

**Blade of Judgment.** Melee or Ranged Weapon Attack: +14 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 10 (1d6 + 7) piercing damage plus 27 (6d8) radiant damage. If the target is a creature, it must succeed on a DC 22 Charisma saving throw, or on its next turn, it can either move or take an action, but not both.

**Revelation.** The veiled presence reveals a glimpse of its otherworldly nature to a creature it can see within 30 feet of itself. The target must succeed on a DC 22 Wisdom saving throw or have the paralyzed condition until the end of its next turn, after which the target is immune to this Revelation for 24 hours.


---

### Reactions

**Uncanny Dodge.** When an attacker the veiled presence can see hits the veiled presence with an attack, the veiled presence halves the attack's damage against it.


---

### Legendary Actions

### 

**Flash Step.** The veiled presence magically teleports, along with any equipment it is wearing or carrying, up to 40 feet to an unoccupied space that it can see.

**Stab (Costs 2 Actions).** The veiled presence makes one Blade of Judgment attack.

**Searing Radiance (Costs 3 Actions).** The veiled presence magically emanates dazzling light in a 10-foot-radius sphere centered on itself until the end of its next turn, during which time attack rolls against it have disadvantage and it has advantage on attack rolls. The sphere moves with the veiled presence. When another creature starts its turn in the light or enters the light for the first time on its turn, that creature must make a DC 22 Constitution saving throw, taking 18 (4d8) radiant damage on a failed save, or half as much damage on a successful one.


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