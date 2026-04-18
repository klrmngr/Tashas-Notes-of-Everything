---
type: pc
race: "Humanoid (half-black dragon)"
class:
 - "Rezmir"
subClass:
 - "CR 7"
cover: "Rezmir.png"
campaign:
locations:
tags:
  - race/half-black dragon
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/hotdq
---
###### Rezmir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Rezmir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-black dragon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13; 15 with the Black Dragon Mask |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Humanoid (half-black dragon) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 16 | 15 | 12 | 14 |
| **Mod** | +4 | +3 | +3 | +2 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 120 ft., passive Perception 11
**Languages:** Common, Draconic, Infernal, Giant, Netherese
**Saving Throws:** Dex +6, Wis +4
**Skills:** Arcana +5, Stealth +9
**Damage Immunities:** acid
**Condition Immunities:** charmed; frightened

---

### Traits

**Special Equipment.** Rezmir has the Black Dragon Mask, Hazirawn, and an insignia of claws.

**Amphibious.** Rezmir can breathe air and water.

**Dark Advantage.** Once per turn, Rezmir can deal an extra 10 (3d6) damage when she hits with a weapon attack, provided Rezmir has advantage on the attack roll.

**Draconic Majesty.** While wearing no armor and wearing the Black Dragon Mask, Rezmir adds her Charisma bonus to her AC (included).

**Immolation.** When Rezmir is reduced to 0 hit points, her body disintegrates into a pile of ash.

**Legendary Resistance (1/Day).** If Rezmir fails a saving throw while wearing the Black Dragon Mask, she can choose to succeed instead.


---

### Actions

**Greatsword (Hazirawn).** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage. If the target is a creature, it can't regain hit points for 1 minute. The target can make a DC 15 Constitution saving throw at the end of each of its turns, ending this effect early on a success.

**Caustic Bolt.** Ranged Spell Attack: +8 to hit, range 90 ft., one target. *Hit:* 18 (4d8) acid damage.

**Acid Breath (Recharge 5–6).** Rezmir breathes acid in a 30-foot line that is 5 feet wide. Each creature in the line must make a DC 14 Dexterity saving throw, taking 22 (5d8) acid damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

If she is wearing the Black Dragon Mask, Rezmir can take up to two legendary actions between each of her turns, taking the actions all at once or spreading them over the round. A legendary action can be taken only at the start or end of a turn.

### 

**Darkness (Costs 2 Actions).** A 15-foot radius of magical darkness extends from a point Rezmir can see within 60 feet of her and spreads around corners. The darkness lasts as long as Rezmir maintains concentration, up to 1 minute. A creature with darkvision can't see through this darkness, and no natural light can illuminate it. If any of the area overlaps with a area of light created by a spell of 2nd level or lower, the spell creating the light is dispelled.

**Melee Attack.** Rezmir makes one melee attack.

**Hide.** Rezmir takes the Hide action.


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