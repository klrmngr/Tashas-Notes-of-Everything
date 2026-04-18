---
type: pc
race: "Fey (wizard)"
class:
 - "Iggwilv the Witch Queen"
subClass:
 - "CR 20"
cover: "Iggwilv the Witch Queen.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/20
  - source/wbtw
---
###### Iggwilv the Witch Queen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Iggwilv the Witch Queen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Fey (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 (robe of the archmagi) |
> | :FasHeart: HP | 255 (30d8 + 120) |
> | :FasUserGroup: Race | Fey (wizard) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 18 | 27 | 12 | 23 |
| **Mod** | +0 | +4 | +4 | +8 | +1 | +6 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 11
**Languages:** Abyssal, Celestial, Common, Draconic, Elvish, Infernal, Sylvan
**Saving Throws:** Int +14, Wis +7, Cha +12
**Skills:** Arcana +20, History +14, Nature +14
**Condition Immunities:** charmed; frightened

---

### Traits

**Boon of Immortality.** Iggwilv is immune to any effect that would age her, and she can't die from old age.

**Legendary Resistance (3/Day).** If Iggwilv fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Iggwilv has advantage on saving throws against spells and other magical effects. (This trait is bestowed by her robe of the archmagi.)

**Special Equipment.** Iggwilv wears an amulet of the planes and a robe of the archmagi.


---

### Actions

**Multiattack.** Iggwilv makes two Bewitching Bolt attacks.

**Bewitching Bolt.** Melee or Ranged Spell Attack: +16 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 25 (5d6 + 8) lightning damage, and if the target is a creature, it must succeed on a DC 22 Wisdom saving throw or be charmed by Iggwilv until the start of her next turn.

**Abyssal Rift (Recharge 5–6).** Iggwilv opens a momentary Abyssal rift within 120 feet of her. The rift is a 20-foot-radius sphere. Each creature in that area must make a DC 22 Constitution saving throw, taking 40 (9d8) necrotic damage on a failed save, or half as much damage on a successful one. In addition, there is a 50 percent chance that 3 [[Hezrou|hezrous]] then appear in unoccupied spaces in the sphere. They act as Iggwilv's allies, take their turns immediately after hers, and can't summon other demons. They remain until they die or until Iggwilv dismisses them as an action.


---

### Bonus Actions

**Fey Step.** Iggwilv teleports, along with any equipment she is wearing or carrying, to an unoccupied space she can see within 30 feet of her.


---

### Reactions

**Negate Spell (2/Day).** When Iggwilv sees a creature within 60 feet of her casting a spell, she tries to interrupt it. If the creature is casting a spell using a spell slot of 8th level or lower, its spell fails and has no effect. If it is casting a 9th-level spell, it must succeed on a DC 22 Intelligence saving throw, or the spells fails and has no effect.


---

### Legendary Actions

### 

**Witchcraft.** Iggwilv uses Spellcasting or Fey Step.

**Dark Speech (Costs 2 Actions).** Iggwilv utters a phrase in a forbidden language and targets one or two creatures she can see within 60 feet of her. Each target must succeed on a DC 22 Wisdom saving throw or take 11 (2d10) psychic damage and be frightened of Iggwilv for 1 minute. A target can repeat the save at the end of each of its turns, ending the effect on itself on a success and thereby becoming immune to Iggwilv's Dark Speech for 24 hours.

**Fey Beguilement (Costs 3 Actions).** Iggwilv targets one creature she can see within 60 feet of her. The target must succeed on a DC 22 Charisma saving throw or be possessed by a fey spirit. While possessed, the target must obey Iggwilv's commands. The target can repeat the saving throw at the end of each of its turns, banishing the fey spirit and ending the effect on itself on a success.


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