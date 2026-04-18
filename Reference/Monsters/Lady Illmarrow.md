---
type: pc
race: "Undead"
class:
 - "Lady Illmarrow"
subClass:
 - "CR 22"
cover: "Lady Illmarrow.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/22
  - source/erlw
---
###### Lady Illmarrow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Lady Illmarrow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 199 (21d8 + 105) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 20 | 27 | 21 | 24 |
| **Mod** | +3 | +3 | +5 | +8 | +5 | +7 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** Common, Draconic, Elvish
**Saving Throws:** Con +12, Int +15, Wis +12
**Skills:** Arcana +15, History +15, Insight +12, Perception +12
**Damage Resistances:** cold; lightning
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Legendary Resistance (3/Day).** If Illmarrow fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Illmarrow has advantage on saving throws against spells and other magical effects.

**Rejuvenation.** Illmarrow's body turns to dust when she drops to 0 hit points, and her equipment is left behind. She gains a new body after 1d10 days, regaining all her hit points and becoming active again. The new body appears within two hundred miles of the location at which she was destroyed.


---

### Actions

**Chill Touch (Cantrip).** Ranged Spell Attack: +15 to hit, range 120 ft., one creature. *Hit:* 18 (4d8) necrotic damage, and the target can't regain hit points until the start of Illmarrow's next turn. If the target is undead, it also has disadvantage on attack rolls against Illmarrow until the end of her next turn.

**Paralyzing Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. *Hit:* 13 (3d6 + 3) slashing damage plus 10 (3d6) cold damage, and the target must succeed on a DC 20 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Poison Breath (Recharge 5–6).** Illmarrow exhales poisonous gas in a 30-foot cone. Each creature in that area must make a DC 20 Constitution saving throw. On a failed save, a creature takes 35 (10d6) poison damage and is poisoned for 1 minute. While poisoned in this way, the creature can't regain hit points. On a successful save, the creature takes half as much damage and isn't poisoned.
A humanoid reduced to 0 hit points by this damage dies and rises at the start of Illmarrow's next turn as a zombie. The zombie acts immediately after Illmarrow in the initiative count and is permanently under her command, following her verbal orders.


---

### Legendary Actions

### 

**Cantrip.** Illmarrow casts a cantrip.

**Paralyzing Claw.** Illmarrow uses her Paralyzing Claw.

**Frightening Presence (Costs 2 Actions).** Illmarrow targets up to three creatures she can see within 30 feet of her. Each target must succeed on a DC 20 Wisdom saving throw or be frightened for 1 minute. A frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to Illmarrow's Frightening Presence for the next 24 hours.

**Poison Breath (Costs 3 Actions).** Illmarrow recharges her Poison Breath and uses it.


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