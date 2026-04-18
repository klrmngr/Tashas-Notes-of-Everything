---
type: pc
race: "Fiend (devil)"
class:
 - "Asmodeus"
subClass:
 - "CR 30"
cover: "Asmodeus.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/30
  - source/coa
---
###### Asmodeus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Asmodeus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 30 (155,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 725 (50d10 + 450) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 21 | 28 | 25 | 30 | 30 |
| **Mod** | +10 | +5 | +9 | +7 | +10 | +10 |

**Speed:** 30 ft., fly 120 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 60 ft., passive Perception 29
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Str +19, Con +18, Int +16, Cha +19
**Skills:** Arcana +16, Deception +28, Insight +28, Intimidation +19, Perception +19, Persuasion +19, Religion +16
**Damage Resistances:** cold
**Damage Immunities:** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Condition Immunities:** blinded; charmed; frightened; paralyzed; poisoned; stunned

---

### Traits

**Antimagic Aura.** Asmodeus has advantage on saving throws against spells and other magical effects. Spells of level 4 or lower can't damage Asmodeus.

**Fiendish Regeneration.** Asmodeus regains 40 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Asmodeus dies only if he starts his turn with 0 hit points and doesn't regenerate. If Asmodeus dies, his body regenerates, returning to life 13 (2d12) days later.

**Legendary Resistance (3/Day).** If Asmodeus fails a saving throw, he can choose to succeed instead.

**Submission Aura.** When a creature moves to be within 120 feet of Asmodeus, they must succeed on a DC 24 Wisdom saving throw or have the frightened condition until they leave the aura. While frightened, creatures kneel before Asmodeus, taking no actions unless he commands otherwise. If Asmodeus deals damage to a kneeling creature, the creature's frightened condition ends. A creature that succeeds the saving throw is immune to this effect for 1 hour.


---

### Actions

**Multiattack.** Asmodeus makes four attacks using Ruby Rod, Chilling Gaze, or a combination of the two. He can replace one of the attacks with Hellish Smite.

**Ruby Rod.** Melee Weapon Attack: +21 to hit, reach 5 ft., one target. *Hit:* 21 (2d8 + 12) necrotic damage, which also reduces the target's hit point maximum by the damage taken. This damage can't reduce a target's hit point maximum below 1. Any effect that removes a disease allows a creature's hit point maximum to return to normal.

**Chilling Gaze.** Ranged Spell Attack: +16 to hit, range 60 ft., one target. *Hit:* 18 (2d10 + 7) cold damage, and the target has a-1 penalty to all attack rolls they make until the end of their next turn. This penalty can stack.

**Hellish Smite.** Asmodeus targets a creature he can see within 300 feet of him, calling down a bolt of hellish lightning. The target must make a DC 24 Dexterity saving throw, taking 14 (4d6) lightning damage plus 14 (4d6) fire damage on a failed save, or half as much damage on a successful one.

**Infernal Word: Stun (Recharge 4–6).** Asmodeus targets a creature he can see within 120 feet of him. The target must make a DC 24 Intelligence saving throw, taking 45 (10d8) force damage on a failed save, or half as much damage on a successful one. A creature that failed the save is stunned for up to 1 minute. The stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success, but taking the damage again on a failed save.

**Hell-Lord's Suggestion (Recharge 5–6).** Asmodeus targets a creature he can see within 120 feet of him. The target must make a DC 24 Charisma saving throw, taking 44 (8d10) psychic damage on a failed save, or half as much damage on a successful one. A creature that failed the save has the charmed condition for up to 1 minute. While charmed, a creature is controlled by Asmodeus, performing only actions that he suggests. A charmed creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success, but taking the damage again on a failed save.

**Fires of the Nine Hells (Recharge 5–6).** Asmodeus chooses a point he can see within 500 feet of him, which explodes into a roaring inferno. All creatures within a 60-foot-radius sphere centered on that point must make a DC 24 Dexterity saving throw, taking 70 (20d6) fire damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Ruby Absorption.** As a reaction to being the sole target of a spell, Asmodeus can attempt to absorb the spell into the Ruby Rod.
Asmodeus rolls (1d20 + 2), and if the result is higher than (10 + spell level), the spell is absorbed into the rod and has no effect.


---

### Legendary Actions

### 

**Channel Ruby Rod.** The Ruby Rod has 66 charges. Asmodeus may spend its charges to cast one of the following spells from it, with a spell save DC of 20: Lesser Restoration (3 charges), Wall of Force (7 charges), Greater Restoration (12 charges), Chain Lightning (15 charges), Prismatic Spray (23 charges), Globe of Invulnerability (33 charges)

**Strike (Costs 2 Actions).** Asmodeus makes a Ruby Rod attack.

**Call Underling (Costs 3 Actions).** Asmodeus summons an allied pit fiend in an unoccupied space that he can see.


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