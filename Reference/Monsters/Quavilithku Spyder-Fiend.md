---
type: pc
race: "Fiend (demon)"
class:
 - "Quavilithku Spyder-Fiend"
subClass:
 - "CR 17"
cover: "Quavilithku Spyder-Fiend.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/17
  - source/veor
---
###### Quavilithku Spyder-Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Quavilithku Spyder-Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 256 (27d10 + 108) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 19 | 17 | 14 | 12 |
| **Mod** | +4 | +3 | +4 | +3 | +2 | +1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 18
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +10, Wis +8
**Skills:** Investigation +9, Perception +8, Stealth +9
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The quavilithku has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The quavilithku can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** When in contact with a web, the quavilithku knows the exact location of any other creature in contact with the same web.

**Web Walker.** The quavilithku ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The quavilithku makes two Bite attacks.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage plus 17 (5d6) poison damage. If the target is a creature, it must succeed on a DC 18 Constitution saving throw or have the poisoned condition for 1 minute. While poisoned in this way, a creature can't regain hit points. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Dissolving Web (Recharge 5–6).** The quavilithku expels acid-drenched webs in a 90-foot cone. Each creature in that area must make a DC 18 Constitution saving throw, taking 44 (8d10) acid damage on a failed save or half as much damage on a successful one. Nonmagical objects in the area that aren't being worn or carried take 44 (8d10) acid damage.


---

### Bonus Actions

**Assess Weakness.** The quavilithku sizes up a creature it can see within 40 feet of itself. Until the start of the quavilithku's next turn, it has advantage on attack rolls against the creature.


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