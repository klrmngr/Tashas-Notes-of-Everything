---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Nycaloth"
subClass:
 - "CR 9"
cover: "Nycaloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/mm
---
###### Nycaloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Nycaloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend (yugoloth) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 19 | 12 | 10 | 15 |
| **Mod** | +5 | +0 | +4 | +1 | +0 | +2 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Skills:** Intimidation +6, Perception +4, Stealth +4
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The nycaloth has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The nycaloth's weapon attacks are magical.


---

### Actions

**Multiattack.** The nycaloth makes two melee attacks, or it makes one melee attack and teleports before or after the attack.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or take 5 (2d4) slashing damage at the start of each of its turns due to a fiendish wound. Each time the nycaloth hits the wounded target with this attack, the damage dealt by the wound increases by 5 (2d4). Any creature can take an action to stanch the wound with a successful DC 13 Wisdom (Medicine) check. The wound also closes if the target receives magical healing.

**Greataxe.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 18 (2d12 + 5) slashing damage.

**Teleport.** The nycaloth magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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