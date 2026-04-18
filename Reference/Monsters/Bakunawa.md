---
type: pc
race: "Dragon"
class:
 - "Bakunawa"
subClass:
 - "CR 12"
cover: "Bakunawa.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/12
  - source/jttrc
---
###### Bakunawa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Bakunawa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 150 (12d20 + 24) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 15 | 14 | 17 | 16 |
| **Mod** | +5 | +1 | +2 | +2 | +3 | +3 |

**Speed:** 20 ft., fly 60 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 21
**Languages:** Celestial, Common, Draconic
**Saving Throws:** Dex +5, Con +6, Wis +7
**Damage Resistances:** lightning; thunder

---

### Traits

**Amphibious.** The bakunawa can breathe air and water.

**Legendary Resistance (3/Day).** If the bakunawa fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The bakunawa makes one Bite attack and one Storm Slam attack.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage plus 7 (2d6) lightning damage. If the target is a Large or smaller creature, it must succeed on a DC 17 Strength saving throw or be swallowed by the bakunawa. A swallowed creature is blinded and restrained, and it has 3 against attacks and other effects outside the bakunawa. At the start of each of the bakunawa's turns, each swallowed creature takes 10 (3d6) lightning damage.
The bakunawa's gullet can hold up to two creatures at a time. If the bakunawa takes 30 damage or more on a single turn from a swallowed creature, the bakunawa must succeed on a DC 16 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 15 feet of the bakunawa. If the bakunawa dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 15 feet of movement, exiting prone.

**Storm Slam.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 9 (1d8 + 5) bludgeoning damage plus 5 (1d10) thunder damage, and the target is pushed up to 10 feet in a horizontal direction away from the bakunawa.


---

### Legendary Actions

### 

**Nimble Glide.** The bakunawa flies or swims up to half its speed. This movement doesn't provoke opportunity attacks.

**Slam.** The bakunawa makes one Storm Slam attack.

**Lightning Strikes (Costs 3 Actions).** The bakunawa arcs lightning at up to two creatures it can see within 60 feet of itself. Each target must succeed on a DC 15 Dexterity saving throw or take 22 (4d10) lightning damage.


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