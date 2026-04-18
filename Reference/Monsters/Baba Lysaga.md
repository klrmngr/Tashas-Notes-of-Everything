---
type: pc
race: "Humanoid (human, shapechanger)"
class:
 - "Baba Lysaga"
subClass:
 - "CR 11"
cover: "Baba Lysaga.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/cos
---
###### Baba Lysaga
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Baba Lysaga.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Humanoid (human, shapechanger) |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 16 | 20 | 17 | 13 |
| **Mod** | +4 | +0 | +3 | +5 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Abyssal, Common, Draconic, Dwarvish, Giant
**Saving Throws:** Wis +7
**Skills:** Arcana +13, Religion +13

---

### Traits

**Shapechanger.** Baba Lysaga can use an action to polymorph into a [[Swarm Of Insects]] (flies), or back into her true form. While in swarm form, she has a walking speed of 5 feet and a flying speed of 30 feet. Anything she is wearing transforms with her, but nothing she is carrying does.

**Blessing of Mother Night.** Baba Lysaga is shielded against divination magic, as though protected by a nondetection spell.


---

### Actions

**Multiattack.** Baba Lysaga makes three attacks with her quarterstaff.

**Quarterstaff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage, or 8 (1d8 + 4) bludgeoning damage if wielded with two hands.

**Summon Swarms of Insects (Recharges after a Short or Long Rest).** Baba Lysaga summons 1d4 swarms of insects. A summoned swarm appears in an unoccupied space within 60 feet of Baba Lysaga and acts as her ally. It remains until it dies or until Baba Lysaga dismisses it as an action.


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