---
type: pc
race: "Elemental"
class:
 - "Firenewt Warrior"
subClass:
 - "CR 1/2"
cover: "Firenewt Warrior.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/1-2
  - source/mpmm
---
###### Firenewt Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Firenewt Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (shield) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 7 | 11 | 8 |
| **Mod** | +0 | +1 | +1 | -2 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Draconic, Ignan
**Damage Immunities:** fire

---

### Traits

**Amphibious.** The firenewt can breathe air and water.


---

### Actions

**Multiattack.** The firenewt makes two Scimitar attacks.

**Scimitar.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage.

**Spit Fire (Recharges after a Short or Long Rest).** The firenewt spits fire at a creature within 10 feet of it. The creature must make a DC 11 Dexterity saving throw, taking 9 (2d8) fire damage on a failed save, or half as much damage on a successful one.


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