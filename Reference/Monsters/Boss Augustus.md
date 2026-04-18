---
type: pc
race: "Monstrosity"
class:
 - "Boss Augustus"
subClass:
 - "CR 9"
cover: "Boss Augustus.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/9
  - source/bmt
---
###### Boss Augustus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Boss Augustus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 17 | 14 | 15 | 12 |
| **Mod** | +4 | +3 | +3 | +2 | +2 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Common, Thieves' cant (can't speak in wolf form)
**Saving Throws:** Str +8, Dex +7
**Skills:** Perception +10, Sleight Of Hand +7, Stealth +7

---

### Traits

**Regeneration.** Augustus regains 10 hit points at the start of his turn. If he takes damage from a silver weapon, this trait doesn't function at the start of his next turn. Augustus dies only if he starts his turn with 0 hit points and doesn't regenerate.

**Special Equipment.** Augustus wields a +2 Longsword.


---

### Actions

**Multiattack.** Augustus makes any combination of two Bite, Claw, or Magic Longsword attacks.

**Bite (Wolf or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 26 (5d8 + 4) piercing damage. If the target is a Humanoid, it must succeed on a DC 15 Constitution saving throw or be cursed with lycanthropy. While cursed in this way, the target retains its alignment, languages, and equipment but otherwise uses the werewolf stat block, excluding actions that require equipment the target doesn't have. During any night when there's a full moon in the sky, the target becomes an NPC under the DM's control and remains so until the night ends. A Remove Curse spell or similar magic ends this curse.

**Claw (Wolf or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 21 (5d6 + 4) piercing damage. If the target is a creature, it must succeed on a DC 16 Strength saving throw or have the prone condition.

**Magic Longsword (Humanoid or Hybrid Form Only).** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 28 (4d10 + 6) slashing damage.


---

### Bonus Actions

**Change Shape.** Augustus polymorphs into a wolf-humanoid hybrid, a wolf, or his humanoid form. His statistics, other than his speed, are the same in each form. Any equipment he is wearing or carrying isn't transformed. He reverts to his humanoid form if he dies.

**Cunning Action.** Augustus takes the Dash, Disengage, or Hide action.


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