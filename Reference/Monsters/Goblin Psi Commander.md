---
type: pc
race: "Aberration (goblinoid)"
class:
 - "Goblin Psi Commander"
subClass:
 - "CR 4"
cover: "Goblin Psi Commander.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/4
  - source/pabtso
---
###### Goblin Psi Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Goblin Psi Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Aberration (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (studded leather armor) |
> | :FasHeart: HP | 58 (13d6 + 13) |
> | :FasUserGroup: Race | Aberration (goblinoid) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 19 | 13 | 17 | 15 | 10 |
| **Mod** | +1 | +4 | +1 | +3 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Goblin, telepathy 60 ft.
**Saving Throws:** Int +5, Wis +4
**Skills:** Stealth +8
**Damage Resistances:** psychic

---

### Traits

**Mental Burst.** When the goblin dies, its pent-up mental energy explodes in a psychic blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence saving throw or take 10 (4d4) psychic damage.

**Mental Fortitude.** The goblin has advantage on saving throws against effects that would make it have the charmed or frightened conditions.


---

### Actions

**Multiattack.** The goblin makes three Psychic Blade attacks.

**Psychic Blade.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* 11 (2d6 + 4) psychic damage, and the target must subtract 1d4 from the next attack roll or saving throw it makes before the end of the goblin's next turn.

**Synaptic Rend (Recharge 5–6).** The goblin unleashes a 30-foot-radius sphere of psychic energy, centered on a point the goblin can see within 60 feet of itself. Each creature in that area must make a DC 13 Intelligence saving throw. On a failed save, a creature takes 14 (4d6) psychic damage and has the incapacitated condition until the end of the goblin's next turn. On a successful save, a creature takes half as much damage only.


---

### Bonus Actions

**Nimble Escape.** The goblin takes the Disengage or Hide action.


---

### Reactions

**Psionic Shield.** When the goblin or one of its allies within 15 feet of it is hit by an attack roll, the goblin conjures a shield of force. The target of the attack gains a +3 bonus to its AC against the triggering attack roll, potentially causing it to miss.


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