---
type: pc
race: "Fiend (devil)"
class:
 - "War Devil"
subClass:
 - "CR 16"
cover: "War Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/16
  - source/coa
---
###### War Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[War Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (devil) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 237 (19d12 + 114) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 23 | 7 | 13 | 9 |
| **Mod** | +7 | -1 | +6 | -2 | +1 | -1 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Str +12, Con +11
**Skills:** Athletics +12, Insight +6, Intimidation +4, Perception +6
**Damage Resistances:** cold
**Damage Immunities:** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Condition Immunities:** frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the war devil's darkvision.

**Fear Aura.** Any hostile creature that starts its turn within 20 feet of the war devil must succeed on a DC 18 Wisdom saving throw or have the frightened condition until the start of the creature's next turn. If a creature's saving throw is successful, the creature is immune to the war devil's Fear Aura for the next 24 hours. This ability doesn't function if the war devil is unconscious.

**Magic Resistance.** The war devil has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The war devil makes two attacks using its Cold- Iron Ranseur, Claws, or a combination of the two.

**Cold-Iron Ranseur.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 23 (3d10 + 7) force damage plus 14 (4d6) cold damage.

**Claws.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 20 (3d8 + 7) slashing damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 20). While a creature is grappled, the war devil can't make Claws attacks.


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