---
type: pc
race: "Humanoid (monk)"
class:
 - "Monastic Operative"
subClass:
 - "CR 5"
cover: "Monastic Operative.png"
campaign:
locations:
tags:
  - race/monk
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/crcotn
---
###### Monastic Operative
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Monastic Operative.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid (monk) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (Unarmored Defense) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (monk) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 14 | 14 | 17 | 11 |
| **Mod** | +1 | +4 | +2 | +2 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common plus two other languages
**Saving Throws:** Dex +7, Wis +6
**Skills:** Acrobatics +7, Insight +6, Investigation +8, Stealth +7

---

### Traits

**Unarmored Defense.** While the operative is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The operative makes three Unarmed Strike attacks, three Cobalt Dart attacks, or a combination thereof.

**Unarmed Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) bludgeoning damage.

**Cobalt Dart.** Ranged Weapon Attack: +7 to hit, range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 3 (1d6) force damage.


---

### Reactions

**Retaliating Strike.** When a creature within 5 feet of the operative hits or misses the operative with a melee attack, the operative makes one Unarmed Strike attack against the attacker.


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