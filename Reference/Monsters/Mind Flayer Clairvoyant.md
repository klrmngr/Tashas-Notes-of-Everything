---
type: pc
race: "Aberration"
class:
 - "Mind Flayer Clairvoyant"
subClass:
 - "CR 11"
cover: "Mind Flayer Clairvoyant.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/11
  - source/pabtso
---
###### Mind Flayer Clairvoyant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Mind Flayer Clairvoyant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (breastplate) |
> | :FasHeart: HP | 156 (24d8 + 48) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 15 | 21 | 17 | 18 |
| **Mod** | +0 | +1 | +2 | +5 | +3 | +4 |

**Speed:** 30 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 15 ft., passive Perception 17
**Languages:** Deep Speech, telepathy 120 ft., Undercommon
**Saving Throws:** Int +9, Wis +7, Cha +8
**Skills:** Arcana +9, Insight +7, Perception +7, Stealth +5
**Damage Resistances:** psychic
**Condition Immunities:** blinded; charmed; frightened

---

### Traits

**Legendary Resistance (3/Day).** If the mind flayer fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The mind flayer has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The mind flayer makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 21 (3d10 + 5) psychic damage. If the target is Medium or smaller, it has the grappled condition (escape DC 17) and must succeed on a DC 17 Intelligence saving throw or have the incapacitated condition until the grapple ends.

**Extract Brain.** Melee Weapon Attack: +9 to hit, reach 5 ft., one incapacitated Humanoid grappled by the mind flayer. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.

**Unleash Void (Recharge 5–6).** The mind flayer opens a rift into the Far Realm, centered on a point the mind flayer can see within 60 feet of itself, and a tentacle lashes across creatures near the rift. Each creature other than mind flayers within 30 feet of the rift must make a DC 17 Intelligence saving throw, after which the tentacle disappears and the rift closes. On a failed save, a creature takes 18 (4d8) cold damage from the rift plus 18 (4d8) psychic damage from the tentacle and has the stunned condition for 1 minute. On a successful save, a creature takes half as much damage only. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Reactions

**Warp Reality.** When hit by an attack roll, the mind flayer gains a +4 bonus to its AC against that attack roll, potentially causing it to miss. Then the mind flayer, along with any equipment it is wearing or carrying, magically teleports up to 60 feet to an unoccupied space it can see.


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