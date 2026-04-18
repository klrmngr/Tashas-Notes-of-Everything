---
type: pc
race: "Aberration"
class:
 - "Alyxian the Tormented"
subClass:
 - "CR 11"
cover: "Alyxian the Tormented.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/11
  - source/crcotn
---
###### Alyxian the Tormented
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Alyxian the Tormented.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 150 (12d12 + 72) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 18 | 22 | 15 | 16 | 20 |
| **Mod** | +5 | +4 | +6 | +2 | +3 | +5 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 17
**Languages:** Celestial, Common, Elvish, telepathy 120 ft.
**Saving Throws:** Str +9, Con +10, Wis +7
**Skills:** Deception +9, Insight +7, Perception +7
**Damage Immunities:** necrotic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; stunned

---

### Traits

**Apotheonic Rejuvenation.** When Alyxian drops to 0 hit points, his body dies and cracks open like a cocoon. Alyxian instantly emerges from the cocoon in his second form, Alyxian the Callous, in the space where his previous form died. His initiative count doesn't change.

**Divinely Blessed.** Alyxian can't be surprised and can't be changed into another form against his will.

**Legendary Resistance (2/Day).** If Alyxian fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Alyxian makes two Grasping Hand attacks.

**Grasping Hand.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) force damage, and if the target is a Medium or smaller creature, it is grappled (escape DC 15). Alyxian has six hands, each of which can grapple one target.

**Void Eyes (Recharge 5–6).** Alyxian targets up to two creatures he can see within 120 feet of himself. Each target must make a DC 17 Constitution saving throw, taking 28 (8d6) necrotic damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Attack.** Alyxian makes one Grasping Hand attack.

**Weapons of Yore (Costs 2 Actions).** Ancient weapons embedded in Alyxian's hide detach from Alyxian and fly about in a 10-foot-radius sphere centered on a point Alyxian can see within 60 feet of himself. A creature takes 18 (4d8) slashing damage when it enters that area for the first time on a turn or starts its turn there. The effect lasts until the end of Alyxian's next turn, when the weapons return to Alyxian and embed themselves in his hide once again (causing him no harm).


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