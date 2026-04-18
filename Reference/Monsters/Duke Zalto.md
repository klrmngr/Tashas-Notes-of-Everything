---
type: pc
race: "Giant"
class:
 - "Duke Zalto"
subClass:
 - "CR 9"
cover: "Duke Zalto.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/skt
---
###### Duke Zalto
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Duke Zalto.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 221 (13d12 + 78) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 9 | 23 | 10 | 14 | 13 |
| **Mod** | +7 | -1 | +6 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Elvish, Giant
**Saving Throws:** Dex +3, Con +10, Cha +5
**Skills:** Athletics +11, Perception +6
**Damage Resistances:** lightning
**Damage Immunities:** fire

---

### Traits

**Siege Monster.** Zalto deals double damage to objects and structures.

**Special Equipment.** Zalto wears a ring of lightning resistance.

**Tackle.** When Zalto enters any enemy's space for the first time on a turn, the enemy must succeed on a DC 19 Strength saving throw or be knocked prone.


---

### Actions

**Multiattack.** Zalto makes two maul attacks.

**Maul.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 28 (6d6 + 7) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. *Hit:* 29 (4d10 + 7) bludgeoning damage.


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