---
type: pc
race: "Humanoid"
class:
 - "Grung Elite Warrior"
subClass:
 - "CR 2"
cover: "Grung Elite Warrior.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/mpmm
---
###### Grung Elite Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Grung Elite Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 49 (9d6 + 18) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 16 | 15 | 10 | 11 | 12 |
| **Mod** | -2 | +3 | +2 | +0 | +0 | +1 |

**Speed:** 25 ft., climb 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Grung
**Saving Throws:** Dex +5
**Skills:** Athletics +2, Perception +2, Stealth +5, Survival +2
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The grung can breathe air and water.

**Poisonous Skin.** Any creature that grapples the grung or otherwise comes into direct contact with the grung's skin must succeed on a DC 12 Constitution saving throw or become poisoned for 1 minute. A poisoned creature no longer in direct contact with the grung can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Standing Leap.** The grung's long jump is up to 25 feet and its high jump is up to 15 feet, with or without a running start.

**Water Dependency.** If the grung isn't immersed in water for at least 1 hour during a day, it suffers 1 level of exhaustion at the end of that day. The grung can recover from this exhaustion only through magic or by immersing itself in water for at least 1 hour.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 5 (2d4) poison damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 5 (2d4) poison damage.

**Mesmerizing Chirr (Recharge 6).** The grung makes a chirring noise to which grungs are immune. Each Humanoid or Beast that is within 15 feet of the grung and able to hear it must succeed on a DC 12 Wisdom saving throw or be stunned until the end of the grung's next turn.


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