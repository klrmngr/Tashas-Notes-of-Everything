---
type: pc
race: "Aberration (mind flayer)"
class:
 - "Refraction of Ilvaash"
subClass:
 - "CR 15"
cover: "Refraction of Ilvaash.png"
campaign:
locations:
tags:
  - race/mind flayer
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/15
  - source/pabtso
---
###### Refraction of Ilvaash
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Refraction of Ilvaash.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Aberration (mind flayer) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 199 (21d12 + 63) |
> | :FasUserGroup: Race | Aberration (mind flayer) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 17 | 23 | 20 | 22 |
| **Mod** | +3 | +0 | +3 | +6 | +5 | +6 |

**Speed:** 10 ft., fly 30 ft. ((hover)), swim 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 15
**Languages:** Common, Deep Speech, telepathy 100 miles, Undercommon
**Saving Throws:** Int +11, Wis +10
**Skills:** Arcana +11, Insight +15, Intimidation +11, Persuasion +11
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; psychic
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Creature Sense.** The refraction is aware of creatures within 100 miles of it that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each one's Intelligence score, but can't sense anything else about it. A creature protected by a mind blank spell, a nondetection spell, or similar magic can't be perceived in this manner.

**Incorporeal Movement.** The refraction can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Legendary Resistance (5/Day).** If the refraction fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The refraction has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The refraction makes two Dissonant Claw attacks.

**Dissonant Claw.** Melee Weapon Attack: +11 to hit, reach 10 ft. or range 120 ft., one creature. *Hit:* 25 (3d12 + 6) psychic damage. If the target is a creature concentrating on a spell, its concentration is broken.

**Mind Blast (Recharge 5–6).** Creatures of the refraction's choice within 60 feet of it must succeed on a DC 19 Intelligence saving throw or take 33 (5d10 + 6) psychic damage and have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Teleport.** The refraction teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied place that it can see.


---

### Legendary Actions

### 

**Mindbreaker.** The refraction targets a creature within 120 feet of itself and disrupts its mental processes, causing the target to have disadvantage on all ability checks, attack rolls, and saving throws until the end of the target's next turn.

**Projected Claw (Costs 2 Actions).** The refraction makes one Dissonant Claw attack.


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