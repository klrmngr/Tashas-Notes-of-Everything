---
type: pc
race: "Humanoid (orc)"
class:
 - "Orc Nurtured One of Yurtrus"
subClass:
 - "CR 1/2"
cover: "Orc Nurtured One of Yurtrus.png"
campaign:
locations:
tags:
  - race/orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/vgm
---
###### Orc Nurtured One of Yurtrus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Orc Nurtured One of Yurtrus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 30 (4d8 + 12) |
> | :FasUserGroup: Race | Humanoid (orc) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 8 | 16 | 7 | 11 | 7 |
| **Mod** | +2 | -1 | +3 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Orc

---

### Traits

**Aggressive.** As a bonus action, the orc can move up to its speed toward a hostile creature that it can see.

**Corrupted Carrier.** When the orc is reduced to 0 hit points, it explodes, and any creature within 10 feet of it must make a DC 13 Constitution saving throw. On a failed save, the creature takes 14 (4d6) poison damage and becomes poisoned. On a success, the creature takes half as much damage and isn't poisoned. A creature poisoned by this effect can repeat the save at the end of each of its turn, ending the effect on itself on a success. While poisoned by this effect, a creature can't regain hit points.

**Nurtured One of Yurtrus.** The orc has advantage on saving throws against poison and disease.


---

### Actions

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage plus 2 (1d4) necrotic damage.

**Corrupted Vengeance.** The orc reduces itself to 0 hit points, triggering its Corrupted Carrier trait.


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