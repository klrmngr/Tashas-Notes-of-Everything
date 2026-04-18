---
type: pc
race: "Monstrosity"
class:
 - "Hoard Mimic"
subClass:
 - "CR 8"
cover: "Hoard Mimic.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/8
  - source/ftd
---
###### Hoard Mimic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Hoard Mimic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 123 (13d12 + 39) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 17 | 10 | 16 | 10 |
| **Mod** | +5 | +1 | +3 | +0 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Con +6, Wis +6
**Skills:** Persuasion +3, Stealth +6
**Condition Immunities:** prone

---

### Traits

**False Appearance (Hoard Form Only).** If the mimic is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the mimic move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the mimic is animate.


---

### Actions

**Multiattack.** The mimic makes one Bite attack and two Pseudopod attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 16 (2d10 + 5) piercing damage plus 7 (2d6) acid damage.

**Pseudopod.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage, and the mimic adheres to the target. A creature adhered to the mimic is also grappled by it (escape DC 16). Until this grapple ends, the target is restrained. Ability checks made to escape this grapple have disadvantage.

**Caustic Mist (Recharge 5–6).** The mimic sprays a fine mist of acid in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw. On a failed save, the creature takes 27 (6d8) acid damage and is blinded until the end of its next turn. On a successful save, the creature takes half as much damage and isn't blinded.

**Shapechanger.** The mimic transforms into a hoard or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.


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