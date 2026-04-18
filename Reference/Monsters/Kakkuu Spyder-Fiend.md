---
type: pc
race: "Fiend (demon)"
class:
 - "Kakkuu Spyder-Fiend"
subClass:
 - "CR 5"
cover: "Kakkuu Spyder-Fiend.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/veor
---
###### Kakkuu Spyder-Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Kakkuu Spyder-Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 14 | 6 | 10 | 10 |
| **Mod** | +3 | +2 | +2 | -2 | +0 | +0 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** understands Abyssal but can't speak
**Saving Throws:** Dex +5, Con +5, Wis +3
**Skills:** Perception +3, Stealth +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The kakkuu has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The kakkuu can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** When in contact with a web, the kakkuu knows the exact location of any other creature in contact with the same web.

**Web Walker.** The kakkuu ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The kakkuu makes a Web Snare attack, uses Reel, and makes a Bite attack.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 14 (2d10 + 3) piercing damage plus 10 (3d6) poison damage.

**Reel.** The kakkuu pulls each creature within 60 feet of itself that is grappled by its Web Snare up to 30 feet straight toward itself.

**Web Snare.** Ranged Weapon Attack: +6 to hit, reach 30/60 ft., one Large or smaller creature. *Hit:* The target has the grappled condition (escape DC 13). While grappled, the target also has the restrained condition. A web snare grappling a creature can be attacked and destroyed (AC 10; 10 hit points; immunity to bludgeoning, poison, and psychic damage).


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