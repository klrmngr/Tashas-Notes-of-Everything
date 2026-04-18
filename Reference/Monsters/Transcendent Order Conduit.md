---
type: pc
race: "Humanoid"
class:
 - "Transcendent Order Conduit"
subClass:
 - "CR 8"
cover: "Transcendent Order Conduit.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/mpp
---
###### Transcendent Order Conduit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Transcendent Order Conduit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (Unarmored Defense) |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 19 | 14 | 10 | 18 | 12 |
| **Mod** | +0 | +4 | +2 | +0 | +4 | +1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common plus one more language
**Saving Throws:** Wis +7, Cha +4
**Skills:** Acrobatics +7, Perception +7, Performance +4

---

### Traits

**Instinctive Reflexes.** The conduit has advantage on initiative rolls, and it can't have disadvantage on attack rolls.

**Unarmored Defense.** While the conduit is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The conduit makes three Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage. If the target is a creature, the conduit can choose one of the following additional effects (up to once per turn each):
- **Incapacitate.** The target must succeed on a DC 15 Constitution saving throw or have the incapacitated condition until the end of the conduit's next turn.
- **Push.** The target is pushed up to 10 feet horizontally away from the conduit.


---

### Reactions

**Deflect Attack.** In response to being hit by an attack roll, the conduit partially deflects the blow. The damage the conduit takes from the attack is reduced by 1d10.

**Don't Be There.** When the conduit must make a saving throw, it can move up to half its speed without provoking opportunity attacks. If its new position moves it out of range or otherwise makes it impossible to be targeted by the effect, the conduit avoids the effect entirely.


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