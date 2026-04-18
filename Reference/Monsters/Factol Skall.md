---
type: pc
race: "Undead (wizard)"
class:
 - "Factol Skall"
subClass:
 - "CR 17"
cover: "Factol Skall.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/17
  - source/aatm
---
###### Factol Skall
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AATM
___

> [!infobox|no-t right]
> ![[Factol Skall.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Undead (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 210 (28d8 + 84) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | AATM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 20 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +5 | +2 | +3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** all
**Saving Throws:** Con +9, Int +11, Wis +8
**Skills:** Arcana +17, History +11, Medicine +8, Perception +8
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Aura of Death.** Creatures within 30 feet of Skall have disadvantage on death saving throws.

**Cosmic Annihilation.** A creature killed by Skall can be restored to life only by means of a true resurrection or wish spell.

**Legendary Resistance (4/Day).** If Skall fails a saving throw, he can choose to succeed instead.

**Rejuvenation.** If Skall dies, he turns to dust. If his orrery of souls hasn't been destroyed, Skall re-forms within the Mortuary in 1d10 days. He appears within 5 feet of the orrery.

**Turn Resistance.** Skall has advantage on saving throws against any effect that turns Undead.


---

### Actions

**Multiattack.** Skall makes one Withering Touch attack or uses Spellcasting. He also uses Death Knell twice.

**Withering Touch.** Melee Spell Attack: +11 to hit, reach 5 ft., one target. *Hit:* 32 (6d8 + 5) cold damage plus 31 (7d8) necrotic damage, and if the target is a creature, it can't regain hit points until the start of Skall's next turn.

**Death Knell.** Skall points his finger at a creature he can see within 120 feet of himself, filling the target's mind with visions of death and the plangent toll of an iron bell. The target must succeed on a DC 19 Wisdom saving throw or take 14 (4d6) psychic damage and have the frightened condition until the start of Skall's next turn.

**Fog of Death (1/Day).** Skall exudes a killing fog in a 30-foot-radius sphere centered on himself. The sphere spreads around corners, and its area is heavily obscured. The fog lasts until the start of Skall's next turn, and it can't be dispersed by wind. It does not move with him.
Each creature that enters the fog for the first time on a turn or starts its turn there must make a DC 19 Constitution saving throw, taking 28 (8d6) necrotic damage and 28 (8d6) poison damage on a failed save, or half as much damage on a successful one. A Medium or smaller Humanoid killed by this damage becomes a zombie under Skall's control. The zombie acts on Skall's initiative but immediately after his turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.


---

### Reactions

**Baleful Counterspell.** Skall chatters his teeth to interrupt a creature he can see within 60 feet of himself that is casting a spell. If the spell is 4th level or lower, it fails and has no effect. If the spell is 5th level or higher, Skall makes an Intelligence check (DC 10 + the spell's level). On a successful check, the spell fails and has no effect. Whatever the spell's level, the caster takes 10 (3d6) necrotic damage if the spell fails.

**Near-Death Experience.** In response to being hit by an attack, Skall teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see.


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