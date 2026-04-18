---
type: pc
race: "Aberration"
class:
 - "Woe Strider"
subClass:
 - "CR 7"
cover: "Woe Strider.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/7
  - source/mot
---
###### Woe Strider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Woe Strider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 110 (13d10 + 39) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 8 | 14 | 14 |
| **Mod** | +4 | +2 | +3 | -1 | +2 | +2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** telepathy 120 ft.
**Skills:** Intimidation +5, Perception +5
**Condition Immunities:** frightened

---

### Traits

**Antimagic Cone.** The woe strider's open mouth creates an area of antimagic, as in the antimagic field spell, in a 60-foot cone. At the start of each of its turns, the woe strider decides which way the cone faces and whether its mouth is open or closed.


---

### Actions

**Multiattack.** The woe strider makes two claw attacks and one bite attack. If both claws hit the same creature, the target is grappled (escape DC 14).

**Claw.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 3 (1d6) psychic damage.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature that is grappled, incapacitated, or restrained. *Hit:* 13 (2d8 + 4) piercing damage plus 16 (3d10) psychic damage. In addition, each magic item the creature is carrying that isn't an artifact has its magical properties suppressed for 1 minute.


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