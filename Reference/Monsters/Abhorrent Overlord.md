---
type: pc
race: "Fiend"
class:
 - "Abhorrent Overlord"
subClass:
 - "CR 9"
cover: "Abhorrent Overlord.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/mot
---
###### Abhorrent Overlord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Abhorrent Overlord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 18 | 16 | 15 | 14 | 16 |
| **Mod** | +5 | +4 | +3 | +2 | +2 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Con +7, Cha +7
**Skills:** Deception +7, Intimidation +7, Persuasion +7
**Damage Resistances:** cold; necrotic
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Insatiable Greed.** The abhorrent overlord can sense the presence of gold within 1,000 feet of itself. It can determine which location has the greatest amount of gold and can sense the direction to that site. If the gold is being moved, it knows the direction of the movement. It can't locate gold if any thickness of clay or lead, even a thin sheet, blocks a direct path between it and the gold.

**Magic Resistance.** The abhorrent overlord has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The abhorrent overlord makes two attacks with its claws.

**Claws.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage plus 14 (4d6) necrotic damage. The abhorrent overlord regains hit points equal to half the amount of necrotic damage dealt if the target is a creature.

**Storm of Crows (Recharge 6).** The abhorrent overlord conjures a swarm of spectral crows and harpies in a 20-foot-radius sphere centered on a point the overlord can see within 120 feet of it. The sphere remains for 1 minute or until the overlord loses concentration (as if concentrating on a spell), and its area is lightly obscured and 3.
Any creature that moves into the area for the first time on a turn or starts its turn there must make a DC 15 Constitution saving throw. A creature takes 16 (3d10) slashing damage plus 16 (3d10) psychic damage on a failed save, or half as much damage on a successful one.


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