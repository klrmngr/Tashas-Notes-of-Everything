---
type: pc
race: "Fiend"
class:
 - "Barghest"
subClass:
 - "CR 4"
cover: "Barghest.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/4
  - source/mpmm
---
###### Barghest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Barghest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 14 | 13 | 12 | 14 |
| **Mod** | +4 | +2 | +2 | +1 | +1 | +2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Common, Goblin, Infernal, telepathy 60 ft.
**Skills:** Deception +4, Intimidation +4, Perception +5, Stealth +4
**Damage Resistances:** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Fire Banishment.** When the barghest starts its turn engulfed in flames that are at least 10 feet high or wide, it must succeed on a DC 15 Charisma saving throw or be instantly banished to Gehenna

**Soul Feeding.** The barghest can feed on the corpse of a Fey or Humanoid it killed within the past 10 minutes. This feeding takes at least 1 minute, and it destroys the corpse. The victim's soul is trapped in the barghest for 24 hours, after which time it is digested and the person is incapable of being revived. If the barghest dies before the soul is digested, the soul is released. While a soul is trapped in the barghest, any magic that tries to restore the soul to life has a 50 chance of failing and being wasted.


---

### Actions

**Multiattack.** The barghest makes one Bite attack and one Claw attack.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage.


---

### Bonus Actions

**Change Shape.** The barghest transforms into a Small goblin or back into its true form. Other than its size and speed, its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. The barghest reverts to its true form if it dies.


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