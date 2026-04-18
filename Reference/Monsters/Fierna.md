---
type: pc
race: "Fiend (devil)"
class:
 - "Fierna"
subClass:
 - "CR 25"
cover: "Fierna.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/25
  - source/coa
---
###### Fierna
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Fierna.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 367 (35d8 + 210) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 25 | 22 | 22 | 22 | 29 |
| **Mod** | +3 | +7 | +6 | +6 | +6 | +9 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 24
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +15, Con +14, Wis +14, Cha +17
**Skills:** Acrobatics +15, Deception +25, Insight +14, Intimidation +17, Perception +14, Persuasion +25
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Fear Aura.** When a creature starts their turn within 120 feet of Fierna, they must succeed on a DC 22 Wisdom saving throw or have the frightened condition until they leave the aura. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

**Fiendish Regeneration.** Fierna regains 20 hit points at the start of her turn. If she takes radiant damage this trait doesn't function at the start of her next turn. Fierna dies only if she starts her turn with 0 hit points and is unable to regenerate.

**Legendary Resistance (3/Day).** If Fierna fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Fierna has advantage on saving throws against spells and other magical effects.

**Princess of Hellfire.** Fire conjured by Fierna becomes Hellfire. It ignores resistances and immunities to fire damage, deals double damage to creatures vulnerable to fire or necrotic damage, can't be extinguished through any means, and is capable of melting stone or igniting inflammable objects.


---

### Actions

**Multiattack.** Fierna makes three attacks using Flame Blade, Mote of Flame, or a combination of the two.

**Flame Blade.** Melee Spell Attack: +20 to hit, reach 5 ft., one target. *Hit:* 23 (4d6 + 9) fire damage.

**Mote of Flame.** Fierna targets a creature she can see within 90 feet of her. The target must make a DC 25 Dexterity saving throw, taking 22 (3d8 + 9) fire damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Wreath of Flames.** When hit by a melee attack and Fierna can see her attacker, she covers herself in Hellfire, and the attacker takes 13 (3d8) fire damage.


---

### Legendary Actions

### 

**Blade.** Fierna makes a Flame Blade attack.

**Conjure Hellfire (Costs 2 Actions).** Fierna chooses a point she can see within 150 feet of her. All creatures in a 20-foot-radius sphere centered on that point must make a DC 25 Dexterity saving throw, taking 28 (8d6) fire damage on a failed save, or half as much damage on a successful one.

**Call Underling (Costs 3 Actions).** Fierna summons an allied [[Spined Devil]] in an unoccupied space that she can see.


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