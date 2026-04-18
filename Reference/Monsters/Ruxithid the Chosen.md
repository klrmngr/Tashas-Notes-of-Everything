---
type: pc
race: "Aberration (goblinoid)"
class:
 - "Ruxithid the Chosen"
subClass:
 - "CR 5"
cover: "Ruxithid the Chosen.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/pabtso
---
###### Ruxithid the Chosen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Ruxithid the Chosen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Aberration (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 88 (16d8 + 16) |
> | :FasUserGroup: Race | Aberration (goblinoid) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 19 | 12 | 18 | 15 | 12 |
| **Mod** | +2 | +4 | +1 | +4 | +2 | +1 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Goblin, telepathy 60 ft.
**Saving Throws:** Int +7, Wis +5
**Skills:** Insight +5, Perception +5, Stealth +10
**Damage Resistances:** psychic

---

### Traits

**Legendary Resistance (2/Day).** When Ruxithid fails a saving throw, he can choose to succeed instead.

**Mental Fortitude.** Ruxithid has advantage on saving throws against the charmed and frightened conditions.


---

### Actions

**Multiattack.** Ruxithid makes two Psi-Charged Scimitar attacks.

**Psi-Charged Scimitar.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 7 (2d6) psychic damage.


---

### Bonus Actions

**Brain Tendrils (Recharge 5–6).** Ruxithid unleashes a flurry of crystalline psychic tendrils from his brain, targeting one creature that he can see within 30 feet of himself. The target must succeed on a DC 15 Dexterity saving throw or take 9 (2d8) psychic damage and have the stunned condition until the start of Ruxithid's next turn.

**Combat Command.** Ruxithid commands one allied creature he can see within 60 feet of himself to strike. The creature can immediately use its reaction to make one melee weapon attack against a target within its reach.


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