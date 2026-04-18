---
type: pc
race: "Giant"
class:
 - "Spirit Troll"
subClass:
 - "CR 11"
cover: "Spirit Troll.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/11
  - source/mpmm
---
###### Spirit Troll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Spirit Troll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 130 (20d10 + 20) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 17 | 13 | 8 | 9 | 16 |
| **Mod** | -5 | +3 | +1 | -1 | -1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Giant
**Skills:** Perception +3
**Damage Resistances:** acid; cold; fire
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; prone; restrained; unconscious

---

### Traits

**Incorporeal Movement.** The troll can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Regeneration.** The troll regains 10 hit points at the start of each of its turns. If the troll takes psychic or force damage, this trait doesn't function at the start of the troll's next turn. The troll dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The troll makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 19 (3d10 + 3) psychic damage, and the target must succeed on a DC 15 Wisdom saving throw or be stunned for 1 minute. The stunned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 19 (3d10 + 3) psychic damage.


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