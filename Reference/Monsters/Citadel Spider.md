---
type: pc
race: "Monstrosity"
class:
 - "Citadel Spider"
subClass:
 - "CR 18"
cover: "Citadel Spider.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/18
  - source/veor
---
###### Citadel Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Citadel Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 310 (20d20 + 150) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 21 | 6 | 12 | 9 |
| **Mod** | +8 | +0 | +5 | -2 | +1 | -1 |

**Speed:** 50 ft., climb 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 11
**Languages:** —
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Legendary Resistance (3/Day).** If the spider fails a saving throw, it can choose to succeed instead.

**Spider Climb.** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Walker.** The spider ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The spider makes two Bite attacks. It can replace one of these attacks with a use of Web Bomb.

**Bite.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 19 (2d10 + 8) piercing damage plus 7 (2d6) poison damage.

**Web Bomb.** Ranged Weapon Attack: +14 to hit, range 300 ft./600 ft., one target. *Hit:* 24 (3d10 + 8) bludgeoning damage, and the target and all creatures within 10 feet of it must succeed on a DC 19 Dexterity saving throw or take 10 (3d6) acid damage and have the restrained condition until the start of the spider's next turn.


---

### Reactions

**Absorb Blow.** In response to being hit with an attack roll, the spider's carapace absorbs some of the blow, reducing the damage it takes by 11 (2d10).


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