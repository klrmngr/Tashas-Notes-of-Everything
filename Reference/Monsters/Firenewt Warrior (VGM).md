---
type: pc
race: "Humanoid (firenewt)"
class:
 - "Firenewt Warrior"
subClass:
 - "CR 1/2"
cover: "Firenewt Warrior.png"
campaign:
locations:
tags:
  - race/firenewt
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/vgm
---
###### Firenewt Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Firenewt Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (firenewt) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (chain shirt, shield) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (firenewt) |
> | :FasBook: Source | Volo's Guide to Monsters |

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

**Multiattack.** The firenewt makes two attacks with its scimitar.

**Scimitar.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage.

**Spit Fire (Recharges after a Short or Long Rest).** The firenewt spits fire at a creature within 10 feet of it. The creature must make a DC 11 Dexterity saving throw, taking 9 (2d8) fire damage on a failed save, or half as much damage on a successful one


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