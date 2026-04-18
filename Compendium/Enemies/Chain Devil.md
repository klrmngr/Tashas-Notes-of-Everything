---
type: pc
race: "Devil"
class:
 - "Chain Devil"
subClass:
 - "CR 8"
cover: "Chain Devil.png"
campaign: "THE DROWNED CROWN"
locations:
  - "[[Drow Warship]]"
tags:
  - race/devil
  - affinity/hostile
  - campaign/theDrownedCrown
---
###### Chain Devil
:FasPerson: Boss &nbsp; | &nbsp; :FasMapLocationDot: [[Drow Warship]]
___

> [!infobox|no-t right]
> ![[Chain Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Chain Devil (Kyton) |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 85 (10d8 + 40) |
> | :FasUserGroup: Race | Devil |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 18 | 11 | 12 | 14 |
| **Mod** | +4 | +2 | +4 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 15
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Con +8, Wis +5, Cha +6
**Skills:** Perception +5
**Damage Resistances:** Cold; bludgeoning, piercing, and slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** Fire, poison
**Condition Immunities:** Poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the chain devil's darkvision.

**Magic Resistance.** Advantage on saving throws against spells and other magical effects.

**Bound Guardian** *(flavor)*. While the infernal collar is intact, the chain devil obeys the Drow crew's commands. If the collar is destroyed, the devil acts freely — it may attack Drow and party alike, or focus entirely on whoever it hates most.

---

### Actions

**Multiattack.** Two chain attacks. If Animate Chains is active, each animated chain may also make one attack.

**Chain.** *Melee:* +8 to hit, reach 10 ft. *Hit:* 11 (2d6 + 4) slashing damage. The target is **grappled** (escape DC 14) if the devil isn't already grappling a creature, and the target is **restrained** until the grapple ends.

**Animate Chains *(Recharge 5–6)*.** Up to four chains within 60 ft. sprout razor barbs and animate under the devil's control (must not be worn or carried). Each animated chain: AC 20, 20 HP, resistance to piercing, immunity to psychic and thunder. They act on the devil's turn, each making one chain attack. An animated chain can grapple one creature but can't attack while grappling. Reverts if reduced to 0 HP or the devil is incapacitated.

---

### Reactions

**Unnerving Mask.** When a creature the devil can see starts its turn within 30 ft., the devil can appear as one of that creature's departed loved ones or bitter enemies. DC 14 Wis save or **frightened until end of that creature's turn.**

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
