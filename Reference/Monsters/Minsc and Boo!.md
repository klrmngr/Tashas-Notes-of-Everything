---
type: pc
race: "Humanoid (human)"
class:
 - "Minsc and Boo!"
subClass:
 - "CR 10"
cover: "Minsc and Boo!.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mabjov
---
###### Minsc and Boo!
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Minsc and Boo!.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 (studded leather) |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 10 | 10 | 10 |
| **Mod** | +5 | +1 | +4 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Sylvan
**Saving Throws:** Str +9, Con +8
**Skills:** Athletics +9, Perception +4, Survival +8

---

### Traits

**Boo, The Miniature Giant Space Hamster.** Boo is Minsc's animal companion. Boo is a miniature giant space hamster and has the statistics of a rat.

**Favored Enemy.** Minsc's favored enemy is evil. When he hits an evil creature with a melee attack he deals an additional 7 (2d6) slashing damage.

**Reckless.** At the start of his turn, Minsc may choose to gain advantage on all melee weapon attack rolls during that turn, but attack rolls against him have advantage until the start of his next turn.


---

### Actions

**Multiattack.** Minsc makes two Greatsword attacks.

**Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.


---

### Bonus Actions

**Go for the Eyes, Boo.** As a bonus action, Minsc talks to Boo and gains the inspiration to go into a berserker fury, for 1 minute. While in this berserking fury Minsc gains the following:
- Minsc has advantage on Strength checks and Strength saving throws.
- Minsc gains a +4 bonus to damage rolls when using a melee weapon.
- Minsc has resistance to bludgeoning, piercing, and slashing damage.
- Minsc can make a single melee weapon attack as a bonus action on each of his turns.
- Minsc can't be charmed or frightened. If Minsc is charmed or frightened when he enters his berserking fury, the effect is suspended for the duration of the rage
- If Minsc drops to 0 hit points and doesn't die outright, he can make a DC 10 Constitution saving throw. If he succeeds, he drops to 1 hit point instead. Each time he uses this feature after the first, the DC increases by 5. After 24 hours, the DC resets to 10.


---

### Reactions

**Run, Boo, Run.** If Boo takes damage, Minsc can choose to take the damage instead.


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