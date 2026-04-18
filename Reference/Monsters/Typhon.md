---
type: pc
race: "Monstrosity"
class:
 - "Typhon"
subClass:
 - "CR 15"
cover: "Typhon.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/15
  - source/mot
---
###### Typhon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Typhon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 195 (17d12 + 85) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 10 | 20 | 7 | 12 | 13 |
| **Mod** | +7 | +0 | +5 | -2 | +1 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common
**Saving Throws:** Con +10
**Damage Immunities:** acid; necrotic

---

### Traits

**Keen Smell.** The typhon has advantage on Wisdom (Perception) checks that rely on smell.

**Regeneration.** The typhon regains 20 hit points at the start of its turn. If it takes radiant damage, this trait doesn't function at the start of its next turn. The typhon dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The typhon makes three attacks: one with its Flurry of Bites, one to constrict, and one with its maw.

**Flurry of Bites.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 35 (8d6 + 7) piercing damage.

**Constrict.** Melee Weapon Attack: +12 to hit, reach 15 ft., one Large or smaller creature. *Hit:* 17 (3d6 + 7) bludgeoning damage, and the target is grappled (escape DC 19). Until this grapple ends, the target is restrained and takes 17 (3d6 + 7) bludgeoning damage at the start of each of its turns. The typhon can have up to two creatures constricted.

**Maw.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 26 (3d12 + 7) piercing damage plus 19 (3d12) acid damage.


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