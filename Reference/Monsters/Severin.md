---
type: pc
race: "Humanoid (human)"
class:
 - "Severin"
subClass:
 - "CR 11"
cover: "Severin.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/rot
---
###### Severin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Rise of Tiamat
___

> [!infobox|no-t right]
> ![[Severin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Rise of Tiamat |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 16 | 17 | 12 | 20 |
| **Mod** | +0 | +1 | +3 | +3 | +1 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** While wearing the Mask of the Dragon Queen: darkvision 60 ft., passive Perception 11
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Dex +5, Wis +5
**Skills:** Arcana +7, Religion +7
**Damage Resistances:** While wearing the mask of the Dragon Queen: acid, cold, lightning, poison, bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** While wearing the mask of the Dragon Queen: fire
**Condition Immunities:** While wearing the mask of the Dragon Queen:

---

### Traits

**Special Equipment.** Severin has the Mask of the Dragon Queen.

**Draconic Majesty.** Severin adds his Charisma bonus to his AC (included).

**Ignite Enemy.** If Severin deals fire damage to a creature while wearing the Mask of the Dragon Queen, the target catches fire. At the start of each of its turns, the burning target takes 5 (1d10) fire damage. A creature within reach of the fire can use an action to extinguish it.

**Legendary Resistance (5/Day).** While wearing the Mask of the Dragon Queen, if Severin fails a saving throw, he can choose to succeed instead.


---

### Actions

**Burning Touch.** Melee Spell Attack: +9 to hit, reach 5 ft., one target. *Hit:* 18 (4d8) fire damage.

**Flaming Orb.** Ranged Spell Attack: +9 to hit, range 90 ft., one target. *Hit:* 40 (9d8) fire damage.

**Scorching Burst.** Severin chooses a point he can see within 60 feet of him. Each creature within 5 feet of that point must make a DC 17 Dexterity saving throw, taking 18 (4d8) fire damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

If Severin is wearing the Mask of the Dragon Queen, he can take 3 legendary actions, choosing from the options listed. Only one legendary action option can be used at a time and only at the end of another creature's turn. Severin regains spent legendary actions at the start of his turn.

### 

**Attack.** Severin makes one attack.

**Fiery Teleport (Costs 2 Actions).** Severin, along with any objects he is wearing or carrying, teleports up to 60 feet to an unoccupied space he can see. Each creature within 5 feet of Severin before he teleports takes 5 (1d10) fire damage.

**Hellish Chains (Costs 3 Actions).** Severin targets one creature he can see within 30 feet of him. The target is wrapped in magical chains of fire and restrained. The restrained target takes 21 (6d6) fire damage at the start of each of its turns. At the end of its turns, the target can make a DC 17 Strength saving throw, ending the effect on itself on a success.


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