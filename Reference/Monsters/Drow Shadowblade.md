---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Shadowblade"
subClass:
 - "CR 11"
cover: "Drow Shadowblade.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/mpmm
---
###### Drow Shadowblade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Drow Shadowblade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (studded leather) |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 21 | 16 | 12 | 14 | 13 |
| **Mod** | +2 | +5 | +3 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Elvish, Undercommon
**Saving Throws:** Dex +9, Con +7, Wis +6
**Skills:** Perception +6, Stealth +9

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the drow's darkvision.

**Fey Ancestry.** The drow has advantage on saving throws against being charmed, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The drow makes three Shadow Sword attacks. One of the attacks can be replaced by a Hand Crossbow attack. The drow can also use Spellcasting to cast darkness.

**Shadow Sword.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 30/60 ft., one target. *Hit:* 27 (7d6 + 5) necrotic damage.

**Hand Crossbow.** Ranged Weapon Attack: +9 to hit, range 30/120 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned for 1 hour. If the saving throw fails by 5 or more, the target is also unconscious while poisoned in this way. The target regains consciousness if it takes damage or if another creature takes an action to shake it.


---

### Bonus Actions

**Shadow Step.** While in dim light or darkness, the drow teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see that is also in dim light or darkness. It then has advantage on the first melee attack it makes before the end of the turn.


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