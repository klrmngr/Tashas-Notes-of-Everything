---
type: pc
race: "Fiend"
class:
 - "Maelephant Nomad"
subClass:
 - "CR 14"
cover: "Maelephant Nomad.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/14
  - source/coa
---
###### Maelephant Nomad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Maelephant Nomad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 190 (20d10 + 80) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 18 | 14 | 17 | 15 |
| **Mod** | +6 | +0 | +4 | +2 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Infernal, Maelephant
**Saving Throws:** Str +11, Con +9
**Skills:** Athletics +16, Insight +8, Intimidation +7, Perception +8
**Damage Resistances:** acid; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** frightened; poisoned

---

### Traits

**Magic Resistance.** The maelephant has advantage on saving throws against spells and other magical effects.

**Regenerative.** At the start of its turn, if the maelephant has less than half its hit points, it regenerates 20 hit points. This trait doesn't function if the maelephant starts its turn with less than 1 hit point.


---

### Actions

**Multiattack.** The maelephant makes two attacks using its Claw, Trunk, or a combination of the two.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) slashing damage.

**Trunk.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) piercing damage. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 18). Until this grapple ends, the target has the restrained condition. While it is grappling a creature, the maelephant can't use its Trunk attack against other creatures.

**Noxious Breath (Recharge 5–6).** The maelephant releases a cloud of noxious gas. All creatures in a 30-foot cone in front of the maelephant must make a DC 16 Constitution saving throw. Targets take 42 (12d6) acid damage on a failed save, or half as much damage on a successful one. In addition, on a failed save, the creature's Intelligence and Charisma scores become 1. The creature can't cast spells, activate magic items, understand language, or communicate in any intelligible way. The creature can, however, identify its friends, follow them, and even protect them. A feebled creature can repeat the save every minute, ending the effect on a success.


---

### Bonus Actions

**Reckless Charge.** The maelephant moves up to 40 feet towards a creature it can see and if it moves at least 20 feet in a straight line, it may make a Claw attack. On a hit, the target takes an additional 14 (4d6) force damage and has the prone condition.


---

### Reactions

**Defensive Stance.** As a reaction to taking damage, the maelephant enters a defensive stance until the end of its next turn. While in a defensive stance, the maelephant moves at half speed and can't take bonus actions, but its AC increases by 5.


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