---
type: pc
race: "Fiend"
class:
 - "Vargouille"
subClass:
 - "CR 1"
cover: "Vargouille.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/tiny
  - cr/1
  - source/mpmm
---
###### Vargouille
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Vargouille.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Fiend |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 18 (4d4 + 8) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 14 | 4 | 7 | 2 |
| **Mod** | -2 | +2 | +2 | -3 | -2 | -4 |

**Speed:** 5 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands Abyssal, Infernal, and any languages it knew before becoming a vargouille but can't speak
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 10 (3d6) poison damage.

**Abyssal Curse.** The vargouille targets one incapacitated Humanoid within 5 feet of it. The target must succeed on a DC 12 Charisma saving throw or become cursed. The cursed target loses 1 point of Charisma after each hour, as its head takes on fiendish aspects. The curse doesn't advance while the target is in sunlight or the area of a daylight spell; don't count that time. When the cursed target's Charisma becomes 2, it dies, and its head tears from its body and becomes a new vargouille. Casting remove curse, greater restoration, or a similar spell on the target before the transformation is complete can end the curse. Doing so undoes the changes made to the target by the curse.

**Stunning Shriek (Recharge 5–6).** The vargouille shrieks. Each Humanoid and Beast within 30 feet of the vargouille and able to hear it must succeed on a DC 12 Wisdom saving throw or be frightened of the vargouille until the end of the vargouille's next turn. While frightened in this way, a target is stunned. If a target's saving throw is successful or the effect ends for it, the target is immune to the Stunning Shriek of all vargouilles for 1 hour.


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