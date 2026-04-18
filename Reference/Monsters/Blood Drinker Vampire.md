---
type: pc
race: "Undead"
class:
 - "Blood Drinker Vampire"
subClass:
 - "CR 8"
cover: "Blood Drinker Vampire.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/8
  - source/ggr
---
###### Blood Drinker Vampire
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Blood Drinker Vampire.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 17 | 16 | 13 | 19 |
| **Mod** | +3 | +4 | +3 | +3 | +1 | +4 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** the languages it knew in life
**Saving Throws:** Dex +7, Con +6, Wis +4
**Skills:** Intimidation +7, Perception +4, Stealth +7
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks

---

### Actions

**Multiattack.** The vampire makes three melee attacks, only one of which can be a bite attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one willing creature, or a creature that is grappled by the vampire, incapacitated, or restrained. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) necrotic damage. If the target is humanoid, it must succeed on a DC 15 Charisma saving throw or be charmed by the vampire for 1 minute. While charmed in this way, the target is infatuated with the vampire. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Rapier.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Unarmed Strike.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage. The vampire can also grapple the target (escape DC 14) if it is a creature and the vampire has a hand free.


---

### Reactions

**Parry.** The vampire adds 3 to its AC against one melee attack that would hit it. To do so, the vampire must see the attacker and be wielding a melee weapon.


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