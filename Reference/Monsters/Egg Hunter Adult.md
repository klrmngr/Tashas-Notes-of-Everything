---
type: pc
race: "Monstrosity"
class:
 - "Egg Hunter Adult"
subClass:
 - "CR 5"
cover: "Egg Hunter Adult.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/5
  - source/ftd
---
###### Egg Hunter Adult
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Egg Hunter Adult.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 52 (8d6 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 20 | 16 | 3 | 13 | 5 |
| **Mod** | +2 | +5 | +3 | -4 | +1 | -3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** —
**Saving Throws:** Dex +8, Wis +4
**Skills:** Perception +4, Stealth +11
**Condition Immunities:** frightened; poisoned

---

### Traits

**Amphibious.** The egg hunter can breathe air and water.

**False Appearance.** If the egg hunter is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the egg hunter move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the egg hunter is animate. Dragons have disadvantage on this check.


---

### Actions

**Multiattack.** The egg hunter makes two Barbed Proboscis attacks, and it can use Torpor Spores if it's available.

**Barbed Proboscis.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 9 (2d8) necrotic damage, and the egg hunter regains hit points equal to the necrotic damage dealt.

**Torpor Spores (Recharge 5–6).** The egg hunter releases a billow of sparkling blue spores. Each creature in a 30-foot-radius sphere centered on the egg hunter must succeed on a DC 14 Constitution saving throw or be poisoned for 1 minute. While poisoned in this way, the creature can take either an action or a bonus action on its turn but not both, and it can't take reactions. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to this egg hunter's Torpor Spores for the next 24 hours.


---

### Reactions

**Rapid Adaptation.** When the egg hunter takes damage, it gives itself resistance to that damage.


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