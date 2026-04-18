---
type: pc
race: "Fiend (shapechanger)"
class:
 - "Barghest"
subClass:
 - "CR 4"
cover: "Barghest.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/4
  - source/vgm
---
###### Barghest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Barghest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Fiend (shapechanger) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Fiend (shapechanger) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 14 | 13 | 12 | 14 |
| **Mod** | +4 | +2 | +2 | +1 | +1 | +2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Common, Goblin, Infernal, telepathy 60 ft.
**Skills:** Deception +4, Intimidation +4, Perception +5, Stealth +4
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The barghest can use its action to polymorph into a Small goblin or back into its true form. Other than its size and speed, its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. The barghest reverts to its true form if it dies.

**Fire Banishment.** When the barghest starts its turn engulfed in flames that are at least 10 feet high or wide, it must succeed on a DC 15 Charisma saving throw or be instantly banished to Gehenna. Instantaneous bursts of flame (such as a red dragon's breath or a fireball spell) don't have this effect on the barghest.

**Keen Smell.** The barghest has advantage on Wisdom (Perception) checks that rely on smell.

**Soul Feeding.** A barghest can feed on the corpse of a humanoid that it killed that has been dead for less than 10 minutes, devouring both flesh and soul in doing so. This feeding takes at least 1 minute, and it destroys the victim's body. The victim's soul is trapped in the barghest for 24 hours, after which time it is digested. If the barghest dies before the soul is digested, the soul is released.
While a humanoid's soul is trapped in a barghest, any form of revival that could work has only a 50 chance of doing so, freeing the soul from the barghest if it is successful. Once a creature's soul is digested, however, no mortal magic can return that humanoid to life.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage.


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