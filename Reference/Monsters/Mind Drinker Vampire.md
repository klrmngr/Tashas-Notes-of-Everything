---
type: pc
race: "Undead"
class:
 - "Mind Drinker Vampire"
subClass:
 - "CR 4"
cover: "Mind Drinker Vampire.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/ggr
---
###### Mind Drinker Vampire
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Mind Drinker Vampire.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 12 | 19 | 13 | 14 |
| **Mod** | +3 | +4 | +1 | +4 | +1 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** the languages it knew in life
**Saving Throws:** Dex +6, Int +6, Wis +3
**Skills:** Deception +4, Insight +3, Perception +3, Stealth +6
**Damage Resistances:** necrotic

---

### Traits

**Shadow Stealth.** While in dim light or darkness, the vampire can take the Hide action as a bonus action.

**Sunlight Sensitivity.** While in sunlight, the vampire has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The vampire makes two attacks, only one of which can be a bite attack.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one willing creature, or a creature that is grappled by the vampire, incapacitated, or restrained. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Unarmed Strike.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage. The vampire can also grapple the target (escape DC 13) if it is a creature and the vampire has a hand free.

**Mind Siphon (Recharge 5–6).** The vampire targets a creature it can see within 30 feet of it. The target must make a DC 14 Intelligence saving throw, with disadvantage if the vampire has previously consumed the target's blood. On a failed save, the target takes 28 (8d6) psychic damage, and the vampire discerns the target's surface emotions and thoughts. On a successful save, the target takes half as much damage, and the vampire discerns the target's general emotional state but not its thoughts.


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