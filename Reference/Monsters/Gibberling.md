---
type: pc
race: "Aberration"
class:
 - "Gibberling"
subClass:
 - "CR 1/4"
cover: "Gibberling.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1-4
  - source/mabjov
---
###### Gibberling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Gibberling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 10 | 6 | 8 | 8 |
| **Mod** | +0 | +2 | +0 | -2 | -1 | -1 |

**Speed:** 25 ft., burrow 5 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** —
**Skills:** Stealth +4
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Light Sensitivity.** While in bright light, gibberlings have disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Reckless.** At the start of its turn, the gibberling can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against it have advantage until the start of its next turn.


---

### Actions

**Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Swarm.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 10). All gibberlings within 5 feet of the target can use a reaction to make a Dagger attack with advantage on the attack roll.

**Burrow.** The gibberling burrows into the dirt, giving itself the prone condition. It has advantage on Dexterity (Stealth) checks while it is prone.


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