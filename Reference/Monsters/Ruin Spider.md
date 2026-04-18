---
type: pc
race: "Monstrosity"
class:
 - "Ruin Spider"
subClass:
 - "CR 5"
cover: "Ruin Spider.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/bmt
---
###### Ruin Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Ruin Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 105 (14d10 + 28) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 14 | 2 | 13 | 4 |
| **Mod** | +3 | +4 | +2 | -4 | +1 | -3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —
**Skills:** Stealth +10
**Damage Immunities:** acid

---

### Traits

**Ruinous Acid.** Any nonmagical weapon that hits the spider corrodes. After dealing damage, the weapon takes a permanent and cumulative -1 penalty to damage rolls. If its penalty drops to -5, the weapon is destroyed. Nonmagical ammunition made of metal that hits the spider is destroyed after dealing damage.

**Spider Climb.** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** While in contact with a web, the spider knows the exact location of any other creature in contact with the same web.

**Web Walker.** The spider ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The spider makes two Ruinous Bite attacks. It can replace one attack with a use of Web.

**Ruinous Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage and 9 (2d8) acid damage. In addition, if the target is a creature wearing nonmagical armor, the armor takes a permanent and cumulative -1 penalty to the AC it offers. Armor reduced to an Armor Class of 10 is destroyed.

**Web (Recharge 5–6).** Ranged Weapon Attack: +7 to hit, range 30/60 ft., one creature. *Hit:* The target has the restrained condition. As an action, a restrained target can make a DC 13 Strength check, bursting the webbing on a successful check. The webbing can also be destroyed (AC 10; 5 hit points; vulnerability to fire damage; immunity to acid, bludgeoning, poison, and psychic damage).


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