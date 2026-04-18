---
type: pc
race: "Fey (hag)"
class:
 - "Bavlorna Blightstraw"
subClass:
 - "CR 7"
cover: "Bavlorna Blightstraw.png"
campaign:
locations:
tags:
  - race/hag
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/7
  - source/wbtw
---
###### Bavlorna Blightstraw
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Bavlorna Blightstraw.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Fey (hag) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 110 (13d8 + 52) |
> | :FasUserGroup: Race | Fey (hag) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 18 | 16 | 12 | 15 |
| **Mod** | +6 | +0 | +4 | +3 | +1 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 14
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Con +7, Int +6, Wis +4, Cha +5
**Skills:** Arcana +9, Deception +5, Perception +4, Stealth +3

---

### Traits

**Amphibious.** Bavlorna can breathe air and water.

**Boon of Immortality.** Bavlorna is immune to any effect that would age her, and she can't die from old age.

**Widdershins Allergy.** If a creature within 10 feet of Bavlorna uses at least 10 feet of movement to run in place counterclockwise, Bavlorna is overcome by a fit of sneezing and can't cast spells until the end of her next turn. In addition, any creature Bavlorna has swallowed is immediately expelled and falls prone in an unoccupied space within 5 feet of her.


---

### Actions

**Multiattack.** Bavlorna makes one Bite attack and one Withering Ray attack.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage, and the target is grappled (escape DC 16) if it is a Medium or smaller creature. Until the grapple ends, the target is restrained, and Bavlorna can't use her Bite attack on another target.

**Withering Ray.** Ranged Spell Attack: +6 to hit, range 60 ft., one target. *Hit:* 17 (4d6 + 3) necrotic damage.

**Create Lornlings (Recharge 5–6).** Bavlorna creates one or two 1-foot-tall duplicates of herself, called lornlings (use the Quickling stat block in appendix C). Each lornling appears in an unoccupied space within 5 feet of Bavlorna, obeys her commands, and takes its turn immediately after hers. A lornling lasts for 1 hour, until it or Bavlorna dies, or until Bavlorna dismisses it as an action. Bavlorna can have no more than eight lornlings in existence at a time.


---

### Bonus Actions

**Swallow.** Bavlorna swallows a Small or smaller creature she is grappling, ending the grapple on it. The swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside Bavlorna, and it takes 10 (3d6) acid damage at the start of each of its turns. If the swallowed creature is one of Bavlorna's lornlings, Bavlorna gains all the lornling's memories when the acid damage reduces it to 0 hit points.
Bavlorna can have only one creature swallowed at a time. If Bavlorna dies, a swallowed creature is no longer restrained and can escape from the corpse using 5 feet of movement, exiting prone.


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