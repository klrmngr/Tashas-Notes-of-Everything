---
type: pc
race: "Monstrosity"
class:
 - "Harpy Matriarch"
subClass:
 - "CR 5"
cover: "Harpy Matriarch.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/gos
---
###### Harpy Matriarch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Harpy Matriarch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 88 (16d8 + 16) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 12 | 9 | 10 | 16 |
| **Mod** | +1 | +3 | +1 | -1 | +0 | +3 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Saving Throws:** Dex +6, Cha +6
**Skills:** Perception +3

---

### Traits

**Luring Maestro.** While within 60 feet of the matriarch, creatures have disadvantage on saving throws against the matriarch's Luring Song.

**Magic Resistance.** The matriarch has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The matriarch makes two claws attacks.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (3d6 + 3) slashing damage.

**Fleeting Form.** The matriarch can magically disguise itself to resemble a humanoid of roughly similar size and shape for up to 1 hour. It can revert to its true form as a bonus action. This illusion does not hold up to close scrutiny.

**Luring Song.** The matriarch sings a magical melody. Every humanoid and giant within 300 feet of the matriarch that can hear the song must succeed on a DC 14 Wisdom saving throw or be charmed until the song ends. The matriarch must take a bonus action on its subsequent turns to continue singing. It can stop singing at any time. The song ends if the matriarch is incapacitated.
While charmed by the matriarch, a target is incapacitated and ignores the songs of other harpies. If the charmed target is more than 5 feet away from the matriarch, the target must move on its turn toward the matriarch by the most direct route, trying to get within 5 feet. It doesn't avoid opportunity attacks, but before moving into damaging terrain, such as lava or a pit, and whenever it takes damage from a source other than the matriarch, the target can repeat the saving throw. A charmed target can also repeat the saving throw at the end of each of its turns. If the saving throw is successful, the effect ends on it.
A target that successfully saves is immune to this matriarch's song for the next 24 hours.

**Visage of Desire (1/Day).** The matriarch projects a vision into the minds of creatures within 30 feet of it that aren't constructs or undead, showing each creature achieving whatever it most desires. An affected creature must succeed on a DC 14 Wisdom saving throw or drop whatever it is holding and become paralyzed until the end of its next turn.


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