---
type: pc
race: "Aberration"
class:
 - "Balhannoth"
subClass:
 - "CR 11"
cover: "Balhannoth.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/11
  - source/mpmm
---
###### Balhannoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Balhannoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 8 | 18 | 6 | 15 | 8 |
| **Mod** | +3 | -1 | +4 | -2 | +2 | -1 |

**Speed:** 25 ft., climb 25 ft. &nbsp;|&nbsp; **Senses:** blindsight 500 ft. (blind beyond this radius), passive Perception 16
**Languages:** understands Deep Speech, telepathy 1 mile
**Saving Throws:** Con +8
**Skills:** Perception +6
**Condition Immunities:** blinded

---

### Traits

**Legendary Resistance (2/Day).** If the balhannoth fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The balhannoth makes one Bite attack and two Tentacle attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 19 (3d10 + 3) piercing damage.

**Tentacle.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 15) and is moved up to 5 feet toward the balhannoth. Until this grapple ends, the target is restrained, and the balhannoth can't use this tentacle against other targets. The balhannoth has four tentacles.


---

### Legendary Actions

### 

**Bite.** The balhannoth makes one Bite attack against one creature it has grappled.

**Teleport.** The balhannoth teleports, along with any equipment it is wearing or carrying and any creatures it has grappled, up to 60 feet to an unoccupied space it can see.

**Vanish.** The balhannoth magically becomes invisible for up to 10 minutes or until immediately after it makes an attack roll.


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