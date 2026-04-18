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
  - source/vgm
---
###### Shoosuva
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
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
> | :FasHeart: HP | 110 (13d10 + 39) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 17 | 7 | 14 | 9 |
| **Mod** | +4 | +1 | +3 | -2 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Gnoll, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +6, Wis +5
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Rampage.** When it reduces a creature to 0 hit points with a melee attack on its turn, the shoosuva can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Multiattack.** The shoosuva makes two attacks: one with its bite and one with its tail stinger.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 26 (4d10 + 4) piercing damage.

**Tail Stinger.** Melee Weapon Attack: +7 to hit, reach 15 ft., one creature. *Hit:* 13 (2d8 + 4) piercing damage, and the target must succeed on a DC 14 Constitution saving throw or become poisoned. While poisoned, the target is also paralyzed. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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