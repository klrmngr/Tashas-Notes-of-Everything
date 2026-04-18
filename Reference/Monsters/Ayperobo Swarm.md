---
type: pc
race: "Swarm of Tiny Fiends (devil)"
class:
 - "Ayperobo Swarm"
subClass:
 - "CR 12"
cover: "Ayperobo Swarm.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/coa
---
###### Ayperobo Swarm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Ayperobo Swarm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Fiends (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Swarm of Tiny Fiends (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 24 | 14 | 8 | 13 | 13 |
| **Mod** | -4 | +7 | +2 | -1 | +1 | +1 |

**Speed:** 5 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 15
**Languages:** Celestial, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +11, Cha +5
**Skills:** Intimidation +5, Perception +5, Stealth +11, Survival +5
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the ayperobo swarm's darkvision.

**Magic Resistance.** The ayperobo swarm has advantage on saving throws against spells and other magical effects.

**Swarm.** The ayperobo swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny creature. The ayperobo swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Multiattack.** The ayperobo swarm makes three Bite attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 0 ft., one target. *Hit:* 27 (8d4 + 7) piercing damage, or 17 (4d4 + 7) piercing damage if the swarm has half of its hit points (65) or fewer.

**Burrow (Recharge 6).** The ayperobo swarm makes a Bite attack. On a hit, the swarm burrows inside the creature, dealing an additional 35 (10d6) necrotic damage and taking control of the creature. At the start of each of its turns, the target may make a DC 17 Constitution saving throw, expelling the ayperobo swarm and taking 14 (4d6) piercing damage on a success.
While burrowed inside a creature, the ayperobo swarm has 3 against attacks targeting them, and no longer acts on their own initiative. Instead, they take total control over their host, gaining all of its abilities, attacks, and equipment.
They act during the host's turn, taking actions based on their host. If a host dies while the ayperobo swarm is burrowed, they leave the host at the end of the host's turn, rolling initiative if necessary. Creatures acting as hosts to the ayperobo swarm are fully aware of their actions and surroundings, but are incapable of physically operating their body.


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