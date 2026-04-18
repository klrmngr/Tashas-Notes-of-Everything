---
type: pc
race: "Humanoid"
class:
 - "Red Ruin"
subClass:
 - "CR 10"
cover: "Red Ruin.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/dsotdq
---
###### Red Ruin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Red Ruin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (plate, shield) |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 17 | 13 | 14 | 15 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Draconic
**Saving Throws:** Str +8, Dex +5
**Skills:** Athletics +8, Perception +6
**Damage Resistances:** fire

---

### Traits

**Draconic Devotion.** While Red Ruin can see a Dragon that isn't hostile to her, she has advantage on attack rolls.

**Mounted Combat Master.** When Red Ruin is mounted and a creature targets her mount with an attack, Red Ruin can cause the attack to target her instead.

**Mounted Evasion.** When Red Ruin or her mount makes a Dexterity saving throw to take half damage from an effect, they take no damage on a success and half damage on a failure.


---

### Actions

**Multiattack.** Red Ruin makes three Ember Lance attacks.

**Ember Lance.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 10 (1d12 + 4) piercing damage plus 7 (2d6) fire damage. If the target is a Medium or smaller creature, it must succeed on a DC 16 Strength saving throw or fall prone.

**Explosive Hand Crossbow (Recharge 5–6).** Red Ruin fires an explosive crossbow bolt at a point she can see within 120 feet of herself. When the bolt reaches that point, or if it hits an object early, it detonates in a 20-foot-radius sphere. Each creature in that area must make a DC 15 Dexterity saving throw, taking 35 (10d6) fire damage on a failed save, or half as much damage on a successful one.


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