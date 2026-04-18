---
type: pc
race: "Fiend (demon)"
class:
 - "Vrock"
subClass:
 - "CR 6"
cover: "Vrock.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/6
  - source/xmm
---
###### Vrock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Vrock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 152 (16d10 + 64) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 18 | 8 | 13 | 8 |
| **Mod** | +3 | +2 | +4 | -1 | +1 | -1 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Dex +5, Wis +4, Cha +2
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the vrock dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The vrock has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The vrock makes two Shred attacks.

**Shred.** m +6, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage plus 10 (3d6) Poison damage.

**Spores (Recharge 6).** con DC 15, each creature in a 20-foot Emanation originating from the vrock.  The target has the Poisoned condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. While Poisoned, the target takes 5 (1d10) Poison damage at the start of each of its turns. Emptying a flask of Holy Water on the target ends the effect early.

**Stunning Screech (1/Day).** con DC 15, each creature in a 20-foot Emanation originating from the vrock (demons succeed automatically).  10 (3d6) Thunder damage, and the target has the Stunned condition until the end of the vrock's next turn.


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