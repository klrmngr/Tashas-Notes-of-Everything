---
type: pc
race: "Fiend"
class:
 - "Werevulture"
subClass:
 - "CR 4"
cover: "Werevulture.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/bmt
---
###### Werevulture
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Werevulture.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 17 | 11 | 13 | 8 |
| **Mod** | +3 | +2 | +3 | +0 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common (can't speak in vulture form)
**Skills:** Perception +5

---

### Traits

**Regeneration.** The werevulture regains 10 hit points at the start of its turn. If the werevulture takes radiant damage, this trait doesn't function at the start of the werevulture's next turn. The werevulture dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The werevulture makes two Talon attacks, or it makes a Beak attack and a Talon attack.

**Beak (Vulture or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage. If the target is a Humanoid, it must succeed on a DC 13 Constitution saving throw or be cursed until targeted by the Remove Curse spell or a similar effect. If the cursed target drops to 0 hit points, it becomes a werevulture under the DM's control and regains 10 hit points.

**Talon.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 13 (4d4 + 3) slashing damage.

**Longbow (Humanoid or Hybrid Form Only).** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.


---

### Bonus Actions

**Change Shape.** The werevulture polymorphs into a vulture-humanoid hybrid, into a vulture, or back into its humanoid form. Its game statistics, other than its speed, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its humanoid form if it dies.


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