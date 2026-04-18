---
type: pc
race: "Fiend (devil)"
class:
 - "Hutijin"
subClass:
 - "CR 21"
cover: "Hutijin.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/21
  - source/mtf
---
###### Hutijin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Hutijin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 200 (16d10 + 112) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 15 | 25 | 23 | 19 | 25 |
| **Mod** | +8 | +2 | +7 | +6 | +4 | +7 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +14, Wis +11
**Skills:** Intimidation +14, Perception +11
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Infernal Despair.** Each creature within 15 feet of Hutijin that isn't a devil makes saving throws with disadvantage.

**Legendary Resistance (3/Day).** If Hutijin fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Hutijin has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Hutijin's weapon attacks are magical.

**Regeneration.** Hutijin regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Hutijin dies only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Hutijin makes four attacks: one with his bite, one with his claw, one with his mace, and one with his tail.

**Bite.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 15 (2d6 + 8) piercing damage. The target must succeed on a DC 22 Constitution saving throw or become poisoned. While poisoned in this way, the target can't regain hit points, and it takes 10 (3d6) poison damage at the start of each of its turns. The poisoned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Claw.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) slashing damage.

**Mace.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 15 (2d6 + 8) bludgeoning damage.

**Tail.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 19 (2d10 + 8) bludgeoning damage.

**Teleport.** Hutijin magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.


---

### Reactions

**Fearful Voice (Recharge 5–6).** In response to taking damage, Hutijin utters a dreadful word of power. Each creature within 30 feet of him that isn't a devil must succeed on a DC 22 Wisdom saving throw or become frightened of him for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that saves against this effect is immune to Hutijin's Fearful Voice for 24 hours.


---

### Legendary Actions

### 

**Attack.** Hutijin attacks once with his mace.

**Lightning Storm (Costs 2 Actions).** Hutijin releases lightning in a 20-foot radius. All other creatures in that area must each make a DC 22 Dexterity saving throw, taking 18 (4d8) lightning damage on a failed save, or half as much damage on a successful one.

**Teleport.** Hutijin uses his Teleport action.


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