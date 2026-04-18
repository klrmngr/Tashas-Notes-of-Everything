---
type: pc
race: "Fiend (devil)"
class:
 - "Fire Hellion"
subClass:
 - "CR 11"
cover: "Fire Hellion.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/11
  - source/bgg
---
###### Fire Hellion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fire Hellion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Fiend (devil) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 175 (14d12 + 84) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 23 | 16 | 14 | 21 |
| **Mod** | +7 | +0 | +6 | +3 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Common, Giant, Infernal
**Saving Throws:** Wis +6, Cha +9
**Skills:** Arcana +7, Athletics +11, Perception +6
**Damage Immunities:** fire
**Condition Immunities:** charmed; frightened

---

### Traits

**Magic Resistance.** The hellion has advantage on saving throws against spells and other magical effects.

**Soul Taker.** A Giant or a Humanoid that is reduced to 0 hit points by the hellion dies, and its soul rises as a lemure (see the Monster Manual) on Avernus, one of the Nine Hells, in 1d4 hours. If the creature isn't revived before then, it can be restored to life only by a wish spell or by killing the lemure and casting true resurrection on the creature's original body.


---

### Actions

**Multiattack.** The hellion makes two Morningstar attacks.

**Morningstar.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) piercing damage plus 11 (2d10) fire damage. If the target is a creature, it can't regain hit points until the start of the hellion's next turn.

**Infernal Orb.** The hellion hurls a magical ball of fire that explodes in a 20-foot-radius sphere centered on a point the hellion can see within 120 feet of itself. The sphere spreads around corners. Each creature in that area must make a DC 17 Dexterity saving throw. A creature takes 18 (4d8) fire damage and 18 (4d8) necrotic damage on a failed save, or half as much damage on a successful one.


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