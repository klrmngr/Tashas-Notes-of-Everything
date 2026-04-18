---
type: pc
race: "Monstrosity"
class:
 - "Spiderdragon"
subClass:
 - "CR 11"
cover: "Spiderdragon.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/11
  - source/veor
---
###### Spiderdragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Spiderdragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 152 (16d12 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 18 | 16 | 7 | 14 | 18 |
| **Mod** | +5 | +4 | +3 | -2 | +2 | +4 |

**Speed:** 50 ft., climb 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 90 ft., passive Perception 16
**Languages:** Abyssal, Draconic, Undercommon
**Saving Throws:** Str +9, Dex +8
**Skills:** Intimidation +8, Perception +6
**Damage Resistances:** poison; psychic

---

### Traits

**Magic Resistance.** The spiderdragon has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The spiderdragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Walker.** The spiderdragon ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The spiderdragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) piercing damage plus 13 (2d12) poison damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.

**Spiderling Breath (Recharge 5–6).** The spiderdragon exhales venomous spiderlings in a 30-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking 33 (6d10) piercing damage and 33 (6d10) poison damage on a failed save or half as much damage on a successful one.


---

### Bonus Actions

**Stifling Webs (Recharge 5–6).** The spiderdragon spins a 30-foot cube of strong, sticky webbing in an area adjacent to itself. The webbing lasts for 1 minute, is difficult terrain, and lightly obscures its area. A creature that starts its turn in the webbing or enters the webbing for the first time on its turn must succeed on a DC 15 Dexterity saving throw or have the restrained condition while in the web. As an action, a creature can free itself or another creature from the web by succeeding on a DC 15 Strength check.
A 5-foot cube of the web is destroyed if it takes at least 10 acid, fire, or slashing damage on a single turn.


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