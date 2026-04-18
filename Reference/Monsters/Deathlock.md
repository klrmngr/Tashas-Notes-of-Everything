---
type: pc
race: "Undead (warlock)"
class:
 - "Deathlock"
subClass:
 - "CR 4"
cover: "Deathlock.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/mpmm
---
###### Deathlock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Deathlock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Undead (warlock) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 10 | 14 | 12 | 16 |
| **Mod** | +0 | +2 | +0 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** the languages it knew in life
**Saving Throws:** Int +4, Cha +5
**Skills:** Arcana +4, History +4
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Turn Resistance.** The deathlock has advantage on saving throws against any effect that turns Undead.

**Unusual Nature.** The deathlock doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The deathlock makes two Deathly Claw or Grave Bolt attacks.

**Deathly Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) necrotic damage.

**Grave Bolt.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 14 (2d10 + 3) necrotic damage.


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