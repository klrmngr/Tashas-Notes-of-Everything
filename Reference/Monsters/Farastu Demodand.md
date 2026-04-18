---
type: pc
race: "Fiend"
class:
 - "Farastu Demodand"
subClass:
 - "CR 11"
cover: "Farastu Demodand.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/11
  - source/mpp
---
###### Farastu Demodand
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Farastu Demodand.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 195 (26d8 + 78) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 16 | 8 | 12 | 16 |
| **Mod** | +5 | +1 | +3 | -1 | +1 | +3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** Abyssal, Demodand, telepathy 120 ft.
**Saving Throws:** Dex +5, Wis +5
**Skills:** Perception +9, Stealth +5, Survival +5
**Damage Resistances:** cold; fire
**Damage Immunities:** acid; poison
**Condition Immunities:** paralyzed; poisoned; restrained

---

### Traits

**Boundless Movement.** The farastu ignores difficult terrain, and magical effects can't reduce its speed. It can spend 5 feet of movement to automatically remove the grappled condition from itself.

**Magic Resistance.** The farastu has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The farastu can climb difficult surfaces, including upside down on ceilings, without an ability check.


---

### Actions

**Multiattack.** The farastu makes two Claw attacks and one Bite attack.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) slashing damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 15, with disadvantage). The farastu has two claws, each of which can grapple one creature.

**Bite.** Melee Weapon Attack: +9 to hit (with advantage against a creature the farastu is grappling), reach 5 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage plus 24 (7d6) acid damage.

**Summon Demodand (1/Day).** The farastu has a 40 percent chance of summoning 1 farastu demodand. A summoned demodand appears in an unoccupied space within 60 feet of the farastu, acts as an ally of the farastu, and can't summon other demodands. It remains for 1 minute, until it or the farastu dies, or until the farastu dismisses it as an action.


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