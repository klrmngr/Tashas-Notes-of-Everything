---
type: pc
race: "Humanoid"
class:
 - "Nevermind Gnome Mastermind"
subClass:
 - "CR 5"
cover: "Nevermind Gnome Mastermind.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/mcv2dc
---
###### Nevermind Gnome Mastermind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Nevermind Gnome Mastermind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (leather armor) |
> | :FasHeart: HP | 82 (15d6 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 18 | 14 | 20 | 11 | 15 |
| **Mod** | -1 | +4 | +2 | +5 | +0 | +2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Gnomish
**Saving Throws:** Dex +7, Con +5, Int +8
**Skills:** Arcana +8, Investigation +8, Perception +3

---

### Traits

**Always Thinking Ahead.** The mastermind has advantage on initiative rolls.

**Spider Climb.** The mastermind can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check. This trait doesn't function if the mastermind is grappling creatures in both of its clockwork claws.


---

### Actions

**Multiattack.** The mastermind makes two Clockwork Claw attacks. The mastermind can replace one of these attacks with Generate Gadget if it's available.

**Clockwork Claw.** Melee Weapon Attack: +7 to hit, reach 20 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, and if the target is a Medium or smaller creature, the target is grappled (escape DC 15). Until this grapple ends, the target takes 10 (3d6) piercing damage at the start of each of the mastermind's turns. The mastermind has two claws, each of which can grapple only one target.

**Generate Gadget (Recharge 5–6).** The mastermind quickly assembles a clockwork gadget, producing one of the following effects (the mastermind's choice):

**Chattergrab.** Parts of this gadget look like gnashing metal teeth. This gadget hurtles toward a creature the mastermind can see within 60 feet of itself. The creature must succeed on a DC 16 Dexterity saving throw or take 31 (7d8) piercing damage and be incapacitated until the start of the mastermind's next turn.

**Phasmoball.** The mastermind launches this gadget to a point the mastermind can see within 30 feet of itself, where the gadget unleashes a cloud of mind-warping gases in a 10-foot-radius sphere. Each creature within the sphere must succeed on a DC 16 Wisdom saving throw or take 11 (2d10) psychic damage and be frightened of the mastermind until the start of the mastermind's next turn.

**Thunderscream.** This gadget emits a screeching wave of sound in a 30-foot cone originating from the mastermind. Each creature in that area must make a DC 16 Constitution saving throw, taking 21 (6d6) thunder damage on a failed save or half as much damage on a successful one.


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