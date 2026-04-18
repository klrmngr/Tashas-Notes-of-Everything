---
type: pc
race: "Undead"
class:
 - "Boneclaw"
subClass:
 - "CR 12"
cover: "Boneclaw.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/12
  - source/mpmm
---
###### Boneclaw
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Boneclaw.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 150 (20d10 + 40) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 15 | 13 | 15 | 9 |
| **Mod** | +4 | +3 | +2 | +1 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common plus one language spoken by its master
**Saving Throws:** Dex +7, Con +6, Wis +6
**Skills:** Perception +6, Stealth +7
**Damage Resistances:** cold; necrotic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Rejuvenation.** While its master lives, a destroyed boneclaw gains a new body in 1d10 hours, with all its hit points. The new body appears within 1 mile of the boneclaw's master.

**Unusual Nature.** The boneclaw doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The boneclaw makes two Piercing Claw attacks.

**Piercing Claw.** Melee Weapon Attack: +8 to hit, reach 15 ft., one target. *Hit:* 20 (3d10 + 4) piercing damage plus 11 (2d10) necrotic damage. If the target is a creature, the boneclaw can pull the target up to 10 feet toward itself, and the target is grappled (escape DC 14). The boneclaw has two claws. While a claw grapples a target, the claw can attack only that target.

**Shadow Jump (Recharge 5–6).** If the boneclaw is in dim light or darkness, each creature of the boneclaw's choice within 15 feet of it must succeed on a DC 14 Constitution saving throw or take 34 (5d12 + 2) necrotic damage.
The boneclaw then teleports up to 60 feet to an unoccupied space it can see. It can bring one creature it's grappling, teleporting that creature to an unoccupied space it can see within 5 feet of its destination. The destination spaces of this teleportation must be in dim light or darkness.


---

### Bonus Actions

**Shadow Stealth.** While in dim light or darkness, the boneclaw takes the Hide action.


---

### Reactions

**Deadly Reach.** In response to a creature entering a space within 15 feet of it, the boneclaw makes one Piercing Claw attack against that creature.


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