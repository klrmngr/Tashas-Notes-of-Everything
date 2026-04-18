---
type: pc
race: "Monstrosity"
class:
 - "The Angry"
subClass:
 - "CR 13"
cover: "The Angry.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/13
  - source/mtf
---
###### The Angry
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[The Angry.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 255 (30d8 + 120) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 19 | 8 | 13 | 6 |
| **Mod** | +3 | +0 | +4 | -1 | +1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common
**Skills:** Perception +6
**Damage Resistances:** bludgeoning, piercing, slashing while in dim light or darkness

---

### Traits

**Two Heads.** The Angry has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, or knocked unconscious.

**Rising Anger.** If another creature deals damage to the Angry, the Angry's attack rolls have advantage until the end of its next turn, and the first time it hits with a hook attack on its next turn, the attack's target takes an extra 19 (3d12) psychic damage.
On its turn, the Angry has disadvantage on attack rolls if no other creature has dealt damage to it since the end of its last turn.


---

### Actions

**Multiattack.** The Angry makes two hook attacks.

**Hook.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 16 (2d12 + 3) piercing damage.


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