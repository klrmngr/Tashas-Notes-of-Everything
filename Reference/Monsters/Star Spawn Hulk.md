---
type: pc
race: "Aberration"
class:
 - "Star Spawn Hulk"
subClass:
 - "CR 10"
cover: "Star Spawn Hulk.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/10
  - source/mpmm
---
###### Star Spawn Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Star Spawn Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (13d10 + 65) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 8 | 21 | 7 | 12 | 9 |
| **Mod** | +5 | -1 | +5 | -2 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Deep Speech
**Saving Throws:** Dex +3, Wis +5
**Skills:** Perception +5
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened

---

### Traits

**Psychic Mirror.** If the hulk takes psychic damage, each creature within 10 feet of the hulk takes that damage instead; the hulk takes none of the damage. In addition, the hulk's thoughts and location can't be discerned by magic.


---

### Actions

**Multiattack.** The hulk makes two Slam attacks. If both attacks hit the same target, the target also takes 9 (2d8) psychic damage and must succeed on a DC 17 Constitution saving throw or be stunned until the end of the target's next turn.

**Slam.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage.

**Reaping Arms (Recharge 5–6).** The hulk makes a separate Slam attack against each creature within 10 feet of it. Each creature that is hit must also succeed on a DC 17 Dexterity saving throw or be knocked prone.


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