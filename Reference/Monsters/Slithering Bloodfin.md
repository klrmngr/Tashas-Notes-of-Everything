---
type: pc
race: "Aberration"
class:
 - "Slithering Bloodfin"
subClass:
 - "CR 9"
cover: "Slithering Bloodfin.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/9
  - source/crcotn
---
###### Slithering Bloodfin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Slithering Bloodfin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 16 | 2 | 10 | 3 |
| **Mod** | +5 | +2 | +3 | -4 | +0 | -4 |

**Speed:** 5 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 100 ft. (blind beyond this radius), passive Perception 14
**Languages:** —
**Skills:** Perception +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Death Burst.** When the bloodfin dies, it explodes in a cloud of toxic blood. Each creature in a 10-foot-radius sphere centered on the exploding bloodfin, including any creature swallowed by the bloodfin, must succeed on a DC 15 Constitution saving throw or take 10 (3d6) poison damage. A creature inside the bloodfin when it explodes falls prone in the space formerly occupied by the bloodfin and is no longer blinded or restrained by it.

**Water Breathing.** The bloodfin can breathe only underwater.


---

### Actions

**Multiattack.** The bloodfin makes one Bite attack and one Tail attack.

**Bite.** Melee Weapon Attack: +9 to hit (with advantage if the target is a creature missing any hit points), reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage, and if the target is a creature, it is grappled (escape DC 15). Until this grapple ends, the target is restrained, and the bloodfin can't bite another target.

**Tail.** Melee Weapon Attack: +9 to hit (with advantage if the target is a creature missing any hit points), reach 10 ft., one target. *Hit:* 19 (4d6 + 5) bludgeoning damage.


---

### Bonus Actions

**Swallow.** Melee Weapon Attack: +9 to hit, reach 5 ft., one Medium or smaller creature the bloodfin is grappling. *Hit:* The bloodfin swallows the target. The swallowed creature is no longer grappled but is blinded and restrained. It has 3 against attacks and other effects outside the bloodfin, it takes 14 (4d6) necrotic damage at the start of each of its turns, and the bloodfin regains hit points equal to the necrotic damage dealt. A bloodfin can have only one creature swallowed at a time.
If the bloodfin takes 30 damage or more on a single turn from the swallowed creature, the bloodfin must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls prone in a space within 5 feet of the bloodfin and is no longer blinded or restrained by it.


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