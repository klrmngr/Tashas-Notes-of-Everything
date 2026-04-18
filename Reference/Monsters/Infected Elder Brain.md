---
type: pc
race: "Aberration (mind flayer)"
class:
 - "Infected Elder Brain"
subClass:
 - "CR 11"
cover: "Infected Elder Brain.png"
campaign:
locations:
tags:
  - race/mind flayer
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/11
  - source/pabtso
---
###### Infected Elder Brain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Infected Elder Brain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Aberration (mind flayer) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Aberration (mind flayer) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 20 | 21 | 19 | 20 |
| **Mod** | +2 | +0 | +5 | +5 | +4 | +5 |

**Speed:** 5 ft., swim 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 14
**Languages:** telepathy 1 mile; understands Common, Deep Speech, and Undercommon but can't speak
**Saving Throws:** Int +9, Wis +8, Cha +9
**Skills:** Arcana +9, Insight +12

---

### Traits

**Creature Sense.** The elder brain is aware of creatures within 1 mile of itself that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each one's Intelligence score, but can't sense anything else about it. A creature protected by a mind blank spell, a nondetection spell, or similar magic can't be perceived in this manner.

**Magic Resistance.** The elder brain has advantage on saving throws against spells and other magical effects.

**Telepathic Hub.** The elder brain can use its telepathy to initiate and maintain telepathic conversations with up to ten creatures at a time. The elder brain can let those creatures telepathically hear each other while connected in this way.


---

### Actions

**Multiattack.** The elder brain makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +6 to hit, reach 30 ft., one target. *Hit:* 15 (3d8 + 2) bludgeoning damage. If the target is a Huge or smaller creature, it has the grappled condition (escape DC 14) and takes 9 (1d8 + 5) psychic damage at the start of each of its turns until the grapple ends. The elder brain can have up to four targets grappled at a time.

**Mind Blast (Recharge 5–6).** Creatures of the elder brain's choice within 60 feet of itself must succeed on a DC 17 Intelligence saving throw or take 32 (5d10 + 5) psychic damage and have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Psychic Link.** The elder brain targets one creature with the incapacitated condition that the elder brain senses with its Creature Sense trait and establishes a psychic link with the target. Until the link ends, the elder brain can perceive everything the target senses. The target becomes aware that something is linked to its mind once it no longer has the incapacitated condition, and the elder brain can terminate the link at any time (no action required). The target can use an action on its turn to attempt to break the link, doing so with a successful DC 17 Charisma check. If the target breaks the link this way, the target takes 10 (3d6) psychic damage. The link also ends if the target and the elder brain are more than 1 mile apart. The elder brain can form psychic links with up to ten creatures at a time.


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