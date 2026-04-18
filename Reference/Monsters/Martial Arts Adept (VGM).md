---
type: pc
race: "Humanoid (any race)"
class:
 - "Martial Arts Adept"
subClass:
 - "CR 3"
cover: "Martial Arts Adept.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/vgm
---
###### Martial Arts Adept
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Martial Arts Adept.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 13 | 11 | 16 | 10 |
| **Mod** | +0 | +3 | +1 | +0 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any one language (usually Common)
**Skills:** Acrobatics +5, Insight +5, Stealth +5

---

### Traits

**Unarmored Defense.** While the adept is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The adept makes three unarmed strikes or three dart attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage. If the target is a creature, the adept can choose one of the following additional effects:
- The target must succeed on a DC 13 Strength saving throw or drop one item it is holding (adept's choice).
- The target must succeed on a DC 13 Dexterity saving throw or be knocked prone.
- The target must succeed on a DC 13 Constitution saving throw or be stunned until the end of the adept's next turn.

**Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


---

### Reactions

**Deflect Missile.** In response to being hit by a ranged weapon attack, the adept deflects the missile. The damage it takes from the attack is reduced by 1d10 + 3. If the damage is reduced to 0, the adept catches the missile if it's small enough to hold in one hand and the adept has a hand free.


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