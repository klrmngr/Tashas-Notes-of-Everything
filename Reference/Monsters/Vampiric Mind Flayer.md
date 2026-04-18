---
type: pc
race: "Undead"
class:
 - "Vampiric Mind Flayer"
subClass:
 - "CR 5"
cover: "Vampiric Mind Flayer.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/vrgr
---
###### Vampiric Mind Flayer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Vampiric Mind Flayer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (10d8 + 40) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 5 | 15 | 18 |
| **Mod** | +4 | +4 | +4 | -3 | +2 | +4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** telepathy 120 ft. but can only project emotions
**Saving Throws:** Dex +7, Int +0, Wis +5, Cha +7
**Skills:** Perception +5, Stealth +7
**Damage Resistances:** necrotic; psychic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Spider Climb.** The mind flayer can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Sensitivity.** While in sunlight, the mind flayer has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Unusual Nature.** The mind flayer doesn't require air, food, or sleep.


---

### Actions

**Multiattack.** The mind flayer makes two Claw attacks or one Claw attack and one Tentacles attack.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 10 (3d6) necrotic damage.

**Tentacles.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 7 (1d6 + 4) piercing damage, and if the target is a creature, it is grappled (escape DC 15).

**Drink Sapience.** The mind flayer targets one creature it is grappling. The target must succeed on a DC 15 Wisdom saving throw or take 14 (4d6) psychic damage and gain 1 level of exhaustion. The mind flayer regains a number of hit points equal to the psychic damage dealt. A creature reduced to 0 hit points by the psychic damage dies.


---

### Bonus Actions

**Disrupt Psyche (Recharge 5–6).** The mind flayer magically emits psionic energy in a 30-foot-radius sphere centered on itself. Each creature in that area must succeed on a DC 15 Intelligence saving throw or be incapacitated for 1 minute. The incapacitated creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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