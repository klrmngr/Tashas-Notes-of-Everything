---
type: pc
race: "Humanoid (human)"
class:
 - "Lothar"
subClass:
 - "CR 9"
cover: "Lothar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mabjov
---
###### Lothar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Lothar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 210 (28d8 + 84) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 16 | 11 | 10 | 10 |
| **Mod** | +4 | +3 | +3 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 50 ft. (in raven and hybrid forms) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Orc
**Skills:** Insight +4, Perception +4, Stealth +7, Survival +8
**Damage Immunities:** bludgeoning, piercing, slashing damage from nonmagical weapons that aren't silvered

---

### Traits

**Mimicry.** Lothar can mimic simple sounds he has heard, such as a person whispering, a baby crying, or an animal chittering. A creature that hears the sounds can tell they are imitations with a successful DC 15 Wisdom (Insight) check.


---

### Actions

**Multiattack (Humanoid or Hybrid Form Only).** Lothar makes three Greataxe attacks.

**Greataxe (Humanoid or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 10 (1d12 + 4) slashing damage, 14 (1d12 + 8) while in a rage.

**Beak (Raven or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage in raven form, or 6 (1d4 + 4) piercing damage in hybrid form. If the target is Humanoid, it must succeed on a DC 15 Constitution saving throw or be cursed with wereraven lycanthropy.

**Change Shape.** Lothar can use his action to polymorph into a raven-humanoid hybrid, or into a Small raven, or back into his true form, which is Humanoid. His statistics, other than his size, are the same in each form. Any equipment he is wearing or carrying isn't transformed. Lothar reverts to his true form if he dies.


---

### Bonus Actions

**Rage.** Lothar rages for 1 minute. During his rage he has advantage on Strength checks and Strength saving throws. He gains a +4 bonus to damage while he is in a rage. He has resistance to bludgeoning, piercing, and slashing damage while in a rage. Lothar can't cast spells while in a rage.


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