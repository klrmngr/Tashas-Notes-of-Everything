---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Ghald"
subClass:
 - "CR 7"
cover: "Ghald.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/large
  - cr/7
  - source/pota
---
###### Ghald
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Ghald.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 102 (12d10 + 36) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 17 | 16 | 14 | 13 | 17 |
| **Mod** | +4 | +3 | +3 | +2 | +1 | +3 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Common, Sahuagin
**Saving Throws:** Dex +6, Con +6, Int +5, Wis +4
**Skills:** Insight +4, Perception +7

---

### Traits

**Assassinate.** During its first turn, Ghald has advantage on attack rolls against any creature that hasn't taken a turn. Any hit Ghald scores against a surprised creature is a critical hit.

**Limited Amphibiousness.** Ghald can breathe air and water, but he needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** Ghald can magically command any shark within 120 feet of him, using a limited telepathy.

**Sneak Attack.** Ghald deals an extra 14 (4d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Ghald's that isn't incapacitated and Ghald doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** Ghald makes three attacks, one with his bite and two with his shortswords.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 9 (2d4 + 4) piercing damage.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 11 (2d6 + 4) piercing damage.

**Garrote.** Melee Weapon Attack: +7 to hit, reach 5 ft., one Medium or Small creature against which Ghald has advantage on the attack roll. *Hit:* 9 (2d4 + 4) bludgeoning damage, and the target is grappled (escape DC 15). Until the grapple ends, the target can't breathe, and Ghald has advantage on attack rolls against it.


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