---
type: pc
race: "Fiend (devil)"
class:
 - "Avatar of Baalzebul"
subClass:
 - "CR 18"
cover: "Avatar of Baalzebul.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/18
  - source/coa
---
###### Avatar of Baalzebul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Avatar of Baalzebul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 285 (30d8 + 150) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 13 | 20 | 17 | 18 | 20 |
| **Mod** | +5 | +1 | +5 | +3 | +4 | +5 |

**Speed:** 20 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Str +11, Cha +11
**Skills:** Deception +11, Insight +10, Intimidation +11, Persuasion +11
**Damage Vulnerabilities:** radiant
**Damage Resistances:** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Stench of the Slug.** Any creature that starts its turn within 10 feet of the avatar must succeed on a DC 19 Constitution saving throw or have the poisoned condition until the start of their next turn. On a successful saving throw, the creature is immune to this stench for 1 hour.


---

### Actions

**Multiattack.** The avatar makes four Sickening Claw attacks. It can replace one of the attacks with Insect Gorge (if available).

**Sickening Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage plus 13 (3d8) acid damage. The target's hit point maximum is reduced by the acid damage taken. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Insect Gorge (Recharge 4–6).** The avatar disgorges a swarm of biting flies at a point it can see within 300 feet of itself. Each creature within a 20-foot-radius sphere centered on that point must make a DC 19 Constitution saving throw. A creature takes 55 (10d10) piercing damage on a failed save, or half as much damage on a successful one. The biting flies persist for 1 minute or until the avatar is slain. A creature must also make this saving throw when it enters the insects' area for the first time on a turn or ends its turn there.

**Caustic Slimepool (1/Day).** The avatar causes caustic slime to emanate from itself, covering a 15-foot-radius circle. Each creature within the slime must succeed on a DC 19 Dexterity saving throw or have the grappled condition (escape DC 17). A grappled creature takes 21 (6d6) acid damage at the start of its turn.


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