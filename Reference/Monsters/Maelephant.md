---
type: pc
race: "Fiend"
class:
 - "Maelephant"
subClass:
 - "CR 10"
cover: "Maelephant.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/10
  - source/mpp
---
###### Maelephant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Maelephant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (half plate armor) |
> | :FasHeart: HP | 161 (17d10 + 68) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 18 | 10 | 16 | 12 |
| **Mod** | +4 | +0 | +4 | +0 | +3 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Infernal
**Saving Throws:** Str +8, Con +8
**Skills:** Perception +7
**Damage Resistances:** acid; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** frightened; poisoned

---

### Traits

**Magic Resistance.** The maelephant has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The maelephant makes one Barbed Trunk attack and two Glaive attacks.

**Barbed Trunk.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage plus 13 (2d12) poison damage. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 14). Until this grapple ends, the target has the restrained condition. While it is grappling a creature, the maelephant can't use its barbed trunk to attack other creatures.

**Glaive.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) slashing damage.

**Mind Poison (Recharge 5–6).** The maelephant expels poisonous gas from its trunk in a 60-foot cone. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 39 (6d12) poison damage and has the poisoned condition. While poisoned in this way, the creature loses all weapon and skill proficiencies, it can't cast spells, it can't understand language, and it has disadvantage on Intelligence saving throws. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, the target takes half as much damage only and is immune to this maelephant's Mind Poison for 24 hours.


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