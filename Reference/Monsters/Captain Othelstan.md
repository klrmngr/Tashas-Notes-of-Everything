---
type: pc
race: "Humanoid (human)"
class:
 - "Captain Othelstan"
subClass:
 - "CR 5"
cover: "Captain Othelstan.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/hotdq
---
###### Captain Othelstan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Captain Othelstan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (splint armor, shield) |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 16 | 13 | 14 | 12 |
| **Mod** | +4 | +0 | +3 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Draconic, Giant
**Saving Throws:** Str +7, Con +6
**Skills:** Athletics +7, Intimidation +7, Perception +5, Religion +4

---

### Traits

**Action Surge (Recharges on a Short or Long Rest).** On his turn, Othelstan can take one additional action.

**Tiamat's Blessing of Retribution.** When Othelstan takes damage that reduces him to 0 hit points, he immediately regains 20 hit points. If he has 20 hit points or fewer at the end of his next turn, he dies.


---

### Actions

**Multiattack.** Othelstan attacks twice with his flail or spear, or makes two ranged attacks with his spears.

**Flail.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage.

**Spear.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


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