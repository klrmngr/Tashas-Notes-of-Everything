---
type: pc
race: "Fiend (demon)"
class:
 - "Bulezau"
subClass:
 - "CR 3"
cover: "Bulezau.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/3
  - source/mpmm
---
###### Bulezau
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Bulezau.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 17 | 8 | 9 | 6 |
| **Mod** | +2 | +2 | +3 | -1 | -1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 9
**Languages:** Abyssal, telepathy 60 ft.
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Rotting Presence.** When any creature that isn't a demon starts its turn within 30 feet of the bulezau, that creature must succeed on a DC 13 Constitution saving throw or take 3 (1d6) necrotic damage.

**Standing Leap.** The bulezau's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.

**Sure-Footed.** The bulezau has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.


---

### Actions

**Barbed Tail.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 8 (1d12 + 2) piercing damage plus 4 (1d8) necrotic damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw against disease or become poisoned until the disease ends. While poisoned in this way, the target sports festering boils, coughs up flies, and sheds rotting skin, and the target must repeat the saving throw after every 24 hours that elapse. On a successful save, the disease ends. On a failed save, the target's hit point maximum is reduced by 4 (1d8). The target dies if its hit point maximum is reduced to 0.


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