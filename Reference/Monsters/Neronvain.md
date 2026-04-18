---
type: pc
race: "Humanoid (elf)"
class:
 - "Neronvain"
subClass:
 - "CR 9"
cover: "Neronvain.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/rot
---
###### Neronvain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Rise of Tiamat
___

> [!infobox|no-t right]
> ![[Neronvain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Rise of Tiamat |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 15 | 16 | 13 | 18 |
| **Mod** | -1 | +3 | +2 | +3 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Draconic, Elvish, Infernal
**Saving Throws:** Con +5, Wis +4
**Skills:** Arcana +6, Perception +4
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Draconic Majesty.** Neronvain adds his Charisma bonus to his AC (included).

**Fey Ancestry.** Magic can't put Neronvain to sleep.


---

### Actions

**Multiattack.** Neronvain makes two attacks, either with his shortsword or Eldritch Arrow.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 13 (3d8) poison damage.

**Eldritch Arrow.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 11 (2d10) force damage plus 9 (2d8) poison damage.

**Poisonous Cloud (2/Day).** Poison gas fills a 20-foot-radius sphere centered on a point Neronvain can see within 50 feet of him. The gas spreads around corners and remains until the start of Neronvain's next turn. Each creature that starts its turn in the gas must succeed on a DC 16 Constitution saving throw or be poisoned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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