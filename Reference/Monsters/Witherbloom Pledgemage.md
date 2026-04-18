---
type: pc
race: "Humanoid (druid)"
class:
 - "Witherbloom Pledgemage"
subClass:
 - "CR 4"
cover: "Witherbloom Pledgemage.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/scc
---
###### Witherbloom Pledgemage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Witherbloom Pledgemage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (druid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 (15 with vociferous form) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (druid) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 13 | 14 | 17 | 11 |
| **Mod** | +0 | +2 | +1 | +2 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common plus any two languages
**Saving Throws:** Con +3, Wis +5
**Skills:** Medicine +5, Nature +6, Perception +7
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Regeneration.** As long as the pledgemage has at least 1 hit point remaining, the pledgemage regains 5 hit points at the start of its turn.

**Verdant Talisman.** At the end of a 10-minute ritual, the pledgemage can touch one willing creature (including itself) and bestow upon it a small talisman imbued with magic. Upon receiving the talisman, the creature gains 10 temporary hit points, and it can add 1d6 to its initiative rolls while it wears the talisman. These benefits last for 1 hour or until the pledgemage conducts another ritual to bestow another talisman. When the benefits expire, the talisman crumbles to dust.


---

### Actions

**Briar Vine.** Melee Spell Attack: +5 to hit, reach 15 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 18 (4d8) poison damage. If the target is a Large or smaller creature, the apprentice can pull it up to 10 feet closer to itself.


---

### Bonus Actions

**Vociferous Form (1/Day).** The pledgemage transforms into an avatar of plants and shadow. While in this form, the pledgemage adds its Wisdom modifier to its AC if it isn't wearing armor or wielding a shield, and it has advantage on attack rolls against any creature missing hit points. This form lasts for 1 minute or until the pledgemage is reduced to 0 hit points.


---

### Reactions

**Wither Burst.** When the pledgemage sees a creature within 30 feet of itself drop to 0 hit points, the pledgemage channels the expended life essence and targets another creature it can see within 30 feet of itself. The target must succeed on a DC 13 Constitution saving throw or become poisoned for 1 minute. While poisoned in this way, the target takes 3 (1d6) poison damage at the start of each of its turns. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success.


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