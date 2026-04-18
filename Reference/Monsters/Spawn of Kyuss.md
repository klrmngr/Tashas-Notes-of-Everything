---
type: pc
race: "Undead"
class:
 - "Spawn of Kyuss"
subClass:
 - "CR 5"
cover: "Spawn of Kyuss.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/mpmm
---
###### Spawn of Kyuss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Spawn of Kyuss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 76 (9d8 + 36) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 18 | 5 | 7 | 3 |
| **Mod** | +3 | +0 | +4 | -3 | -2 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Wis +1
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Regeneration.** The spawn of Kyuss regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or a body of running water. If the spawn takes acid, fire, or radiant damage, this trait doesn't function at the start of the spawn's next turn. The spawn is destroyed only if it starts its turn with 0 hit points and doesn't regenerate.

**Worms.** If the spawn of Kyuss is targeted by an effect that cures disease or removes a curse, all the worms infesting it wither away, and it loses its Burrowing Worm action.

**Unusual Nature.** The spawn of Kyuss requires no air, food, drink, or sleep.


---

### Actions

**Multiattack.** The spawn of Kyuss makes two Claw attacks, and it uses Burrowing Worm.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 7 (2d6) necrotic damage.

**Burrowing Worm.** A worm launches from the spawn of Kyuss at one Humanoid that the spawn can see within 10 feet of it. The worm latches onto the target's skin unless the target succeeds on a DC 11 Dexterity saving throw. The worm is a Tiny Undead with AC 6, 1 hit point, a 2 (-4) in every ability score, and a speed of 1 foot. While on the target's skin, the worm can be killed by normal means or scraped off using an action (the spawn can use Burrowing Worm to launch a scraped-off worm at a Humanoid it can see within 10 feet of the worm). Otherwise, the worm burrows under the target's skin at the end of the target's next turn, dealing 1 piercing damage to it. At the end of each of its turns thereafter, the target takes 7 (2d6) necrotic damage per worm infesting it (maximum of 10d6), and if it drops to 0 hit points, it dies and then rises 10 minutes later as a spawn of Kyuss. If a worm-infested target is targeted by an effect that cures disease or removes a curse, all the worms infesting it wither away.


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