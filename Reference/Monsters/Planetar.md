---
type: pc
race: "Celestial"
class:
 - "Planetar"
subClass:
 - "CR 16"
cover: "Planetar.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/16
  - source/mm
---
###### Planetar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Planetar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 200 (16d10 + 112) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 20 | 24 | 19 | 22 | 25 |
| **Mod** | +7 | +5 | +7 | +4 | +6 | +7 |

**Speed:** 40 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Con +12, Wis +11, Cha +12
**Skills:** Perception +11
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Angelic Weapons.** The planetar's weapon attacks are magical. When the planetar hits with any weapon, the weapon deals an extra 5d8 radiant damage (included in the attack).

**Divine Awareness.** The planetar knows if it hears a lie.

**Magic Resistance.** The planetar has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The planetar makes two melee attacks.

**Greatsword.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 21 (4d6 + 7) slashing damage plus 22 (5d8) radiant damage.

**Healing Touch (4/Day).** The planetar touches another creature. The target magically regains 30 (6d8 + 3) hit points and is freed from any curse, disease, poison, blindness, or deafness.


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