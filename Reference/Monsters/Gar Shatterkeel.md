---
type: pc
race: "Humanoid"
class:
 - "Gar Shatterkeel"
subClass:
 - "CR 15"
cover: "Gar Shatterkeel.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/15
  - source/lr
---
###### Gar Shatterkeel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LR
___

> [!infobox|no-t right]
> ![[Gar Shatterkeel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | LR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 18 | 12 | 20 | 14 |
| **Mod** | +3 | +3 | +4 | +1 | +5 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Aquan, Common
**Skills:** Nature +11, Perception +10, Survival +10
**Damage Resistances:** cold

---

### Traits

**Amphibious.** Gar can breathe air and water.

**Legendary Resistance (3/Day).** If Gar fails a saving throw, he can choose to succeed instead.

**Water Walk.** Gar can stand and move on liquid surfaces as if they were solid ground.

**Watery Fall.** When Gar drops to 0 hit points, his body collapses into a pool of inky water that rapidly disperses. Except for Wave and his claw, anything he was wearing or carrying is left behind.


---

### Actions

**Multiattack.** Gar makes two melee attacks, one with his claw and one with Wave.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 16). Until the grapple ends, Gar can't attack other creatures with his claw.

**Wave.** Melee or Ranged Weapon Attack: +11 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 9 (1d6 + 6) piercing damage or 10 (1d8 + 6) piercing damage when used with two hands. If Gar scores a critical hit with this weapon, the target takes extra necrotic damage equal to half its hit point maximum.

**Umberlee's Wake (Recharge 5–6).** Power ripples out in a 60-foot radius sphere from a point within range (150 ft.) as the will of Umberlee affects all in her watery embrace. Each creature in that area must succeed on a DC 18 Constitution saving throw. On a failed save, the creature can't use reactions, its speed is halved, and it can't make more than one attack on its turn. In addition, the creature can use either an action or a bonus action on its turn, but not both. These effects last for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself with a successful save. This only affects targets that are submerged or floating in water. Gar Shatterkeel and any undead serving him are immune to this effect.


---

### Legendary Actions

### 

**Move.** Gar moves up to his speed without provoking opportunity attacks.

**Claw.** Gar makes one attack with his claw.

**Wave (Costs 2 Actions).** Gar makes one attack with Wave with advantage.


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