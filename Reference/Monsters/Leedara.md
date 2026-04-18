---
type: pc
race: "Undead (elf)"
class:
 - "Leedara"
subClass:
 - "CR 4"
cover: "Leedara.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/dsotdq
---
###### Leedara
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Leedara.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 45 (10d8) |
> | :FasUserGroup: Race | Undead (elf) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 13 | 10 | 10 | 12 | 17 |
| **Mod** | -2 | +1 | +0 | +0 | +1 | +3 |

**Speed:** 0 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Any languages she knew in life
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Ethereal Sight.** Leedara can see 60 feet into the Ethereal Plane when she is on the Material Plane, and vice versa.

**Incorporeal Movement.** Leedara can move through other creatures and objects as if they were difficult terrain. She takes 5 (1d10) force damage if she ends her turn inside an object.


---

### Actions

**Withering Touch.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 17 (4d6 + 3) necrotic damage.

**Etherealness.** Leedara enters the Ethereal Plane from the Material Plane, or vice versa. She is visible on the Material Plane while she is in the Border Ethereal, and vice versa, yet she can't affect or be affected by anything on the other plane.

**Horrifying Visage.** Each non-undead creature within 60 feet of Leedara that can see her must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute. If the save fails by 5 or more, the target also ages 1d4 × 10 years. A frightened target can repeat the saving throw at the end of each of its turns, ending the frightened condition on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to Leedara's Horrifying Visage for the next 24 hours. The aging effect can be reversed with a greater restoration spell, but only within 24 hours of it occurring.

**Possession (Recharge 6).** One humanoid that the ghost can see within 5 feet of it must succeed on a DC 13 Charisma saving throw or be possessed by Leedara; Leedara then disappears, and the target is incapacitated and loses control of its body. Leedara now controls the body but doesn't deprive the target of awareness. Leedara can't be targeted by any attack, spell, or other effect, except ones that turn undead, and she retains her alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. She otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.
The possession lasts until the body drops to 0 hit points, Leedara ends it as a bonus action, or Leedara is turned or forced out by an effect like the dispel evil and good spell. When the possession ends, Leedara reappears in an unoccupied space within 5 feet of the body. The target is immune to Leedara's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

**Change Shape.** Leedara magically assumes the appearance she had in life, and her creature type changes to Humanoid, while retaining her other game statistics. This transformation ends if Leedara is reduced to 0 hit points or uses an action to end it.


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