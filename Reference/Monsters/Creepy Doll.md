---
type: pc
race: "Construct"
class:
 - "Creepy Doll"
subClass:
 - "CR 2"
cover: "Creepy Doll.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/2
  - source/psi
---
###### Creepy Doll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSI
___

> [!infobox|no-t right]
> ![[Creepy Doll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 21 (6d4 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | PSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 13 | 12 | 11 | 10 |
| **Mod** | -2 | +2 | +1 | +1 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** speaks and understands the languages known by its creator
**Skills:** Stealth +4
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed

---

### Traits

**False Appearance.** While the creepy doll remains motionless, it is indistinguishable from an ordinary, inanimate doll.


---

### Actions

**Multiattack.** The creepy doll makes one attack with its scissors and uses Psychic Assault.

**Scissors.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) slashing damage.

**Psychic Assault.** The creepy doll targets one creature it can see within 10 feet of it that has a brain. The target must succeed on a DC 12 Intelligence saving throw or take 11 (2d10) psychic damage. Also on a failure, roll 3d6. If the total equals or exceeds the target's Intelligence score, that score is reduced to 0. The target is stunned until it regains at least one point of Intelligence, as from the greater restoration spell or similar magic.

**Body Exchange.** The creepy doll initiates an Intelligence contest with an incapacitated humanoid within 5 feet of it. If it wins the contest, the creepy doll's spirit inhabits the target's body while the target's spirit is placed into the creepy doll's body. The creepy doll controls the target's body completely. It retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The target retains its alignment, Intelligence, Wisdom, and Charisma while inhabiting the creepy doll's body.
The body exchange lasts until the doll's spirit is forced out by magic. (The dispel evil and good spell will accomplish this, though the doll is not one of the creature types whose possession that spell normally ends.) The body and the doll must be within 5 feet of each other for such an effect to work. The target is immune to this doll's Body Exchange for 24 hours after winning the Intelligence contest or after the exchange ends.


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