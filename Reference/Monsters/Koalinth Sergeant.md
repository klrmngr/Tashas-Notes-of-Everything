---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Koalinth Sergeant"
subClass:
 - "CR 2"
cover: "Koalinth Sergeant.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/gos
---
###### Koalinth Sergeant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Koalinth Sergeant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (scale mail) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 12 | 11 | 10 | 12 |
| **Mod** | +2 | +0 | +1 | +0 | +0 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Goblin
**Saving Throws:** Dex +2, Wis +2
**Skills:** Athletics +4, Perception +2

---

### Traits

**Amphibious.** The koalinth can breathe air and water.

**Martial Advantage.** Once per turn, the sergeant can deal an extra 7 (2d6) damage to a creature it hits with a weapon attack if that creature is within 5 feet of an ally of the sergeant that isn't incapacitated.


---

### Actions

**Multiattack.** The sergeant makes two melee attacks with its trident.

**Trident.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack.

**Hooked Net.** Ranged Weapon Attack: +4 to hit, range 10/30 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage, and the target is restrained. A creature can use its action to make a DC 12 Strength check to free itself or another creature in a hooked net, ending the effect on a success. Dealing 5 slashing damage to the net (AC 12) frees the target without harming it and destroys the net.


---

### Reactions

**Spear the Helpless (2/Day).** Whenever a creature within 30 feet of the sergeant becomes restrained, the sergeant can move its speed toward the restrained creature. If the sergeant ends its move within reach of the restrained creature, it can make a melee attack against it.


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