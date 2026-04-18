---
type: pc
race: "Monstrosity"
class:
 - "Undercity Medusa"
subClass:
 - "CR 6"
cover: "Undercity Medusa.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/6
  - source/ggr
---
###### Undercity Medusa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Undercity Medusa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 16 | 17 | 12 | 15 |
| **Mod** | +3 | +4 | +3 | +3 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Elvish
**Skills:** Deception +5, Insight +4, Perception +4, Stealth +7

---

### Traits

**Magic Resistance.** The medusa has advantage on saving throws against spells and other magical effects.

**Surprise Attack.** During the first round of combat, the medusa has advantage on attack rolls against any creature that is surprised, and it deals an extra 10 (3d6) damage each time it hits such a creature with an attack.


---

### Actions

**Multiattack.** The medusa makes two claw attacks. It can also use Petrifying Gaze before or after making these attacks.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Petrifying Gaze.** The medusa fixes its gaze on one creature within 60 feet of it that it can see and that can see its eyes. The target must make a DC 14 Constitution saving throw. If the saving throw fails by 5 or more, the creature is instantly petrified. Otherwise, a creature that fails the save begins to turn to stone and is restrained. The restrained creature must repeat the saving throw at the end of its next turn, becoming petrified on a failure or ending the effect on a success. The petrification lasts until the creature is freed by a greater restoration spell or similar magic.


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