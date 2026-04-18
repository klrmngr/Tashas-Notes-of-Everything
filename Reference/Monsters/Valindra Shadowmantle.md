---
type: pc
race: "Undead (wizard)"
class:
 - "Valindra Shadowmantle"
subClass:
 - "CR 21"
cover: "Valindra Shadowmantle.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/21
  - source/fraif
---
###### Valindra Shadowmantle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Valindra Shadowmantle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Medium Undead (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 315 (42d8 + 126) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 21 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 19
**Languages:** all
**Saving Throws:** Dex +10, Con +10, Int +12, Wis +9
**Skills:** Arcana +19, History +12, Insight +9, Perception +9
**Damage Resistances:** cold; lightning
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (4/Day or 5/Day in Lair).** If Valindra fails a saving throw, she can choose to succeed instead.

**Spirit Gem.** If destroyed, Valindra re-forms in 1d10 days if her spirit gem is intact, reviving with all her Hit Points. The new body appears in an unoccupied space within her lair.


---

### Actions

**Multiattack.** Valindra makes three attacks, using Eldritch Burst or Paralyzing Touch in any combination. She can replace two attacks with a use of Spellcasting to cast Lightning Bolt (level 5 version).

**Eldritch Burst.** m,r +12, reach 5 ft. or range 120 ft. *Hit:* 31 (4d12 + 5) Force damage.

**Paralyzing Touch.** m +12, reach 5 ft. *Hit:* 14 (2d8 + 5) Cold damage, and the target has the Paralyzed condition until the start of Valindra's next turn.

**Deathly Grasp (Recharge 5–6).** dex DC 20, each creature in a 30-foot Emanation originating from Valindra. 1 39 (6d12) Force damage and the target has the Restrained condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. Subsequent Failures: 39 (6d12) Necrotic damage, and Valindra gains 20 Temporary Hit Points.


---

### Legendary Actions

### 

**Disrupt Life.** con DC 20, each creature that isn't Undead in a 20-foot Emanation originating from Valindra.  21 (6d6) Necrotic damage.  Half damage.  Valindra can't take this action again until the start of her next turn.

**Eldritch Jaunt.** Valindra makes one Eldritch Burst attack. Before or after the attack, Valindra can teleport up to 20 feet to an unoccupied space she can see.

**Life-Rending Gaze.** wis DC 20, one creature Valindra can see within 30 feet.  22 (4d10) Necrotic damage, and the target has the Frightened condition until the end of its next turn.  Half damage only.


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