---
type: pc
race: "Humanoid (human)"
class:
 - "Hurricane"
subClass:
 - "CR 2"
cover: "Hurricane.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/pota
---
###### Hurricane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Hurricane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 13 | 10 | 12 | 10 |
| **Mod** | +1 | +3 | +1 | +0 | +1 | +0 |

**Speed:** 45 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Auran, Common
**Skills:** Acrobatics +5

---

### Traits

**Unarmored Defense.** While the hurricane is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.

**Unarmored Movement.** While the hurricane is wearing no armor and wielding no shield, its walking speed increases by 15 feet (included in its speed).


---

### Actions

**Multiattack.** The hurricane makes two melee attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage.


---

### Reactions

**Deflect Missiles.** When the hurricane is hit by a ranged weapon attack, it reduces the damage from the attack by 1d10 + 9. If the damage is reduced to 0, the hurricane can catch the missile if it is small enough to hold in one hand and the hurricane has at least one hand free.


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