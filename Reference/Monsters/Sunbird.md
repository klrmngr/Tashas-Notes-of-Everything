---
type: pc
race: "Monstrosity"
class:
 - "Sunbird"
subClass:
 - "CR 13"
cover: "Sunbird.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/13
  - source/psx
---
###### Sunbird
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSX
___

> [!infobox|no-t right]
> ![[Sunbird.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 279 (18d20 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | PSX |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 10 | 20 | 13 | 14 | 15 |
| **Mod** | +9 | +0 | +5 | +1 | +2 | +2 |

**Speed:** 20 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Giant Owl, understands Common but can't speak it
**Saving Throws:** Dex +5, Con +10, Wis +7, Cha +7
**Skills:** Perception +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire

---

### Traits

**Death Throes.** When the sunbird dies, it explodes, and each creature within 30 feet of it must make a DC 18 Dexterity saving throw, taking 42 (12d6) fire damage on a failed save, or half as much damage on a successful one. The explosion ignites flammable objects in that area that aren't being worn or carried. The sunbird's body turns to ash, but an egg is left where the sunbird was.

**Fire Aura.** At the start of each of the sunbird's turns, each creature within 5 feet of it takes 11 (2d10) fire damage, and flammable objects in the area that aren't being worn or carried ignite. A creature that touches the sunbird or hits it with a melee attack while within 5 feet of it takes 11 (2d10) fire damage. The aura also sheds bright light in a 60-foot radius and dim light for an additional 60 feet.

**Flyby.** The sunbird doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Keen Hearing and Sight.** The sunbird has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Multiattack.** The sunbird makes two talon attacks.

**Talon.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 16 (2d6 + 9) slashing damage plus 14 (4d6) fire damage, and the target is grappled (escape DC 18). Until this grapple ends, the target is restrained, and the sunbird can't attack another target with that talon. A grappled creature takes 11 (2d10) fire damage at the start of each of the sunbird's turns.


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