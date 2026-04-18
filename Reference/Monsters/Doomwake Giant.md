---
type: pc
race: "Giant"
class:
 - "Doomwake Giant"
subClass:
 - "CR 11"
cover: "Doomwake Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/11
  - source/mot
---
###### Doomwake Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Doomwake Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 162 (13d12 + 78) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 12 | 22 | 12 | 14 | 16 |
| **Mod** | +7 | +1 | +6 | +1 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Giant
**Saving Throws:** Con +10, Wis +6
**Skills:** Intimidation +7, Perception +6
**Damage Immunities:** necrotic; poison
**Condition Immunities:** frightened; poisoned

---

### Traits

**Aura of Erebos.** Any creature that starts its turn within 10 feet of the giant must succeed on a DC 18 Constitution saving throw, or it takes 10 (3d6) necrotic damage and can't regain hit points until the start of its next turn. On a successful saving throw, the creature is immune to the giant's Aura of Erebos for 24 hours.

**Magic Resistance.** The giant has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The giant makes two slam attacks.

**Slam.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 20 (3d8 + 7) bludgeoning damage plus 10 (3d6) necrotic damage.

**Noxious Gust (Recharge 5–6).** The giant exhales a mighty gust that creates a blast of deadly mist in a 60-foot line that is 10 feet wide. Each creature in that line must make a DC 18 Constitution saving throw. On a failed save, the creature takes 36 (8d8) necrotic damage and is knocked prone. On a successful save, a creature takes half as much damage and isn't knocked prone.


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