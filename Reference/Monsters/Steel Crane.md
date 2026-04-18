---
type: pc
race: "Humanoid (human)"
class:
 - "Steel Crane"
subClass:
 - "CR 8"
cover: "Steel Crane.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/cm
---
###### Steel Crane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Steel Crane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (Unarmored Defense) |
> | :FasHeart: HP | 76 (9d8 + 36) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 18 | 13 | 17 | 14 |
| **Mod** | +1 | +4 | +4 | +1 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common
**Saving Throws:** Dex +7, Int +4
**Skills:** Acrobatics +7, Deception +5, Perception +6, Stealth +7
**Damage Resistances:** poison; psychic

---

### Traits

**Unarmored Defense.** While Steel Crane is wearing no armor and wielding no shield, his AC includes his Wisdom modifier.


---

### Actions

**Multiattack.** Steel Crane makes three attacks.

**Force Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) force damage, and if the target is a creature, it must succeed on a DC 15 Constitution saving throw or be stunned until the start of Steel Crane's next turn.

**Whip.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage or, if the target is a creature, Steel Crane can grapple the target instead (escape DC 15). Steel Crane can't make attacks with the whip while using it to grapple a creature. Anytime on his turn, he can release a creature grappled by the whip (no action required).

**Heal Self (Recharges after a Long Rest).** Steel Crane regains 2d8 + 4 hit points, and all levels of exhaustion end on him.


---

### Reactions

**Deflect Missile.** In response to being hit by a ranged weapon attack, Steel Crane deflects the missile. The damage he takes from the attack is reduced by 1d10 + 10. If the damage is reduced to 0, Steel Crane catches the missile if it's small enough to hold in one hand and Steel Crane has a hand free.

**Slow Descent (3/Day).** When Steel Crane falls, he can slow his descent, taking no damage from the fall.


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