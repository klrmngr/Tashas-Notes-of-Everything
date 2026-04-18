---
type: pc
race: "Construct"
class:
 - "Glasswork Golem"
subClass:
 - "CR 2"
cover: "Glasswork Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/2
  - source/wbtw
---
###### Glasswork Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Glasswork Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 10 | 1 | 10 | 1 |
| **Mod** | +1 | +0 | +0 | -5 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Saving Throws:** Dex +2, Con +2, Wis +2
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** If the golem is embedded in a window and motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the golem move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the golem is animate.

**Immutable Form.** The golem is immune to any spell or effect that would alter its form.

**Regeneration.** The golem regains 10 hit points at the start of its turn. If the golem takes bludgeoning or thunder damage, this trait doesn't function at the start of the golem's next turn. The golem is destroyed only if it starts its turn with 0 hit points and doesn't regenerate.

**Unusual Nature.** The golem doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The golem makes two Glass Sword attacks.

**Glass Sword.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage.


---

### Bonus Actions

**Dazzling Light (Recharge 5–6).** Magical, colored light springs from the golem in a 15-foot cone. Each creature in the cone must succeed on a DC 10 Constitution saving throw or be blinded for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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