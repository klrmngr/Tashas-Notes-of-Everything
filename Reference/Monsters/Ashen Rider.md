---
type: pc
race: "Celestial"
class:
 - "Ashen Rider"
subClass:
 - "CR 16"
cover: "Ashen Rider.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/16
  - source/mot
---
###### Ashen Rider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Ashen Rider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 19 | 15 | 21 | 18 |
| **Mod** | +5 | +3 | +4 | +2 | +5 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** all
**Saving Throws:** Str +10, Con +9, Wis +10, Cha +9
**Skills:** History +7, Insight +10, Perception +10
**Damage Immunities:** thunder
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Aura of Silence.** When a creature starts its turn within 30 feet of the ashen rider, the rider can force that creature to make a DC 18 Wisdom saving throw if the rider can see it. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature can't speak and is deafened until the start of its next turn.

**Mount.** If the ashen rider isn't mounted, it can use a bonus action to magically teleport onto the creature serving as its mount, provided the ashen rider and its mount are on the same plane of existence. When it teleports, the ashen rider appears astride the mount along with any equipment it is wearing or carrying.
While mounted and not incapacitated, the ashen rider can't be surprised, and both it and its mount have advantage on Dexterity saving throws. If the ashen rider is reduced to 0 hit points while riding its mount, the mount is reduced to 0 hit points as well.


---

### Actions

**Multiattack.** The ashen rider makes three attacks with its ashen blade or two attacks with its bolt of ash.

**Ashen Blade.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage plus 13 (2d12) radiant damage.

**Bolt of Ash.** Ranged Spell Attack: +10 to hit, range 120 ft., one creature. *Hit:* 22 (4d10) necrotic damage, and the target can't regain hit points until the start of the ashen rider's next turn.


---

### Legendary Actions

### 

**Attack.** The ashen rider makes an attack using its ashen blade or bolt of ash.

**Coordinated Assault (Costs 2 Actions).** The ashen rider makes an attack using its ashen blade or bolt of ash, and then its mount can use its reaction to make a melee weapon attack.

**Reduce to Ash (Costs 3 Actions).** The ashen rider targets a creature it can see within 60 feet of it. The target must succeed on a DC 18 Constitution saving throw, or it takes 27 (5d10) necrotic damage and its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. If the target's hit point maximum is reduced to 0, its body and everything it is wearing and carrying, except for magic items, are reduced to ash. A creature reduced to ash can't be revived by any means short of a wish spell.


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