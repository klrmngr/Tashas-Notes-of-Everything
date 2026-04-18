---
type: pc
race: "Fiend (devil)"
class:
 - "Mammon"
subClass:
 - "CR 26"
cover: "Mammon.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/26
  - source/coa
---
###### Mammon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Mammon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (devil) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 464 (32d12 + 256) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 17 | 26 | 22 | 25 | 25 |
| **Mod** | +9 | +3 | +8 | +6 | +7 | +7 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 120 ft., passive Perception 17
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +11, Con +16, Wis +15, Cha +15
**Skills:** Arcana +14, Deception +15, Insight +15, Intimidation +23, Investigation +14, Persuasion +23
**Damage Resistances:** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede Mammon's darkvision.

**Fiendish Regeneration.** Mammon regains 20 hit points at the start of his turn. If he takes radiant damage this trait doesn't function at the start of his next turn. Mammon only dies if he starts his turn with 0 hit points and is unable to regenerate.

**Legendary Resistance (3/Day).** If Mammon fails a saving throw, he can choose to succeed instead

**Magic Resistance.** Mammon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Mammon uses Fearful Gaze, then makes four attacks using Tail Swipe, Constrict, or a combination of the two.

**Tail Swipe.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 31 (4d10 + 9) bludgeoning damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 21). While grappled, the creature also has the restrained condition, and Mammon can't make Tail Swipe attacks.

**Fearful Gaze.** Mammon focuses his gaze in a 90-foot cone in front of him. Each creature of his choice within the cone must make a DC 23 Wisdom saving throw, taking 19 (3d12) psychic damage on a failed save, or half as much damage on a successful one. Creatures that fail the save have the frightened condition until the end of their next turn.

**Constrict.** Mammon tightens his grip around a creature he has grappled. The target takes 35 (4d12 + 9) bludgeoning damage.

**Golden Gaze (Recharge 6).** Mammon attempts to turn one creature he can see within 60 feet of him into solid gold. The target must make a DC 23 Constitution saving throw. On a failed save, the target's flesh begins to harden, and it has the restrained condition. A restrained creature must repeat the saving throw at the end of each turn. If it successfully saves three times, the effect ends. If it fails three times, it turns to gold and now has the petrified condition. Successes and failures don't need to be consecutive.


---

### Reactions

**Pain Tax.** As a reaction to taking damage, Mammon causes the attacker's valuables to glow red hot. This deals 3 (1d6) fire damage to the attacker for every 100 gold (or equivalent in gems, jewelry, and other coinage) that it currently carries.


---

### Legendary Actions

### 

**Change Form.** Mammon changes his form into that of a pit fiend, maintaining his statistics but losing his actions. He gains the actions and mobility of a pit fiend, including its weapon, and maintains his legendary actions and lair actions. Mammon's serpentine abilities can still recharge while he is in pit fiend form. If Mammon is already a pit fiend, this action changes him back into his serpentine form.

**Golden Touch (Costs 2 Actions).** Mammon recharges Golden Gaze.

**Call Underling (Costs 3 Actions).** Mammon summons an allied horned devil in an unoccupied space that he can see.


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