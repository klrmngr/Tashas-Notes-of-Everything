---
type: pc
race: "Fiend (devil)"
class:
 - "Levistus"
subClass:
 - "CR 26"
cover: "Levistus.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/26
  - source/coa
---
###### Levistus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Levistus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 23 (natural armor) |
> | :FasHeart: HP | 336 (32d8 + 192) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 26 | 22 | 25 | 28 | 26 |
| **Mod** | +4 | +8 | +6 | +7 | +9 | +8 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 35
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 1,000 ft.
**Saving Throws:** Dex +16, Con +14, Int +15, Wis +17
**Skills:** Acrobatics +24, Deception +16, Intimidation +16, Perception +25, Persuasion +16, Stealth +16
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Armor of Ice.** Levistus is always entombed in ice. The ice provides 100 temporary hit points. While Levistus has these temporary hit points, he has vulnerability to fire damage. If Levistus starts his turn with no temporary hit points from the ice, he regains 100 temporary hit points.

**Devil's Sight.** Magical darkness doesn't impede Levistus's darkvision.

**Legendary Resistance (3/Day).** If Levistus fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Levistus has advantage on saving throws against spells and other magical effects.

**Sub-zero.** Cold damage dealt by Levistus ignores resistances and immunities.


---

### Actions

**Multiattack.** Levistus makes three Touch of Stygia or Ice Bolt attacks. He can replace one of the attacks with Blizzard (if available).

**Touch of Stygia.** Melee Spell Attack: +15 to hit, reach 5 ft., one target. *Hit:* 20 (3d8 + 7) psychic damage, and the target must succeed on a DC 23 Intelligence saving throw or have the stunned condition for 1 minute. The target may repeat the saving throw at the end of its turns, ending the effect on a success. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

**Ice Bolt.** Ranged Spell Attack: +15 to hit, range 120 ft., one target. *Hit:* 23 (3d10 + 7) cold damage.

**Blizzard (Recharge 4–6).** Levistus chooses a point he can see within 300 feet of him. Each creature in a 20-foot-radius, 40-foot-high cylinder centered on that point must make a DC 23 Dexterity saving throw. Targets take 13 (3d8) force damage plus 13 (3d8) cold damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Counterspell.** As a reaction to a creature he can see casting a spell, Levistus can attempt to prevent the casting. Levistus makes an Intelligence check (+7) against a DC of (10 + spell level). On a success, the creature's spell fails and has no effect.


---

### Legendary Actions

### 

**Amnesia.** Levistus selects a stunned creature that he can see. The creature must succeed on a DC 23 Charisma saving throw or Levistus erases a specific memory from the target. The memory must be one that the target experienced in the last 24 hours and that lasted no more than 10 minutes. The memory can only be restored with a Remove Curse or a Greater Restoration spell.

**Froststrike.** Levistus makes an Ice Bolt attack. On a hit, the target falls and has the prone condition.

**Call Underling (Costs 3 Actions).** Levistus summons an allied [[Ice Devil]] in an unoccupied space that he can see.


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