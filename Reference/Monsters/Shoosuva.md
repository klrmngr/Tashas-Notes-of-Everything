---
type: pc
race: "Fiend (demon)"
class:
 - "Shoosuva"
subClass:
 - "CR 8"
cover: "Shoosuva.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/8
  - source/mpmm
---
###### Shoosuva
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Shoosuva.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 17 | 7 | 14 | 9 |
| **Mod** | +4 | +1 | +3 | -2 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Gnoll, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +6, Wis +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Actions

**Multiattack.** The shoosuva makes one Bite attack and one Tail Stinger attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 26 (4d10 + 4) piercing damage.

**Tail Stinger.** Melee Weapon Attack: +7 to hit, reach 15 ft., one creature. *Hit:* 13 (2d8 + 4) piercing damage, and the target must succeed on a DC 14 Constitution saving throw or become poisoned. While poisoned in this way, the target is also paralyzed. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Rampage.** When it reduces a creature to 0 hit points with a melee attack on its turn, the shoosuva can move up to half its speed and make one Bite attack.


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