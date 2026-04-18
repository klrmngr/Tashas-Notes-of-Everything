---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Arcanaloth"
subClass:
 - "CR 12"
cover: "Arcanaloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/xmm
---
###### Arcanaloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Arcanaloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 175 (27d8 + 54) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 14 | 20 | 16 | 17 |
| **Mod** | +3 | +1 | +2 | +5 | +3 | +3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 17
**Languages:** all; telepathy 120 ft.
**Saving Throws:** Dex +5, Con +6, Int +9, Wis +7
**Skills:** Arcana +9, Deception +7, Insight +7, Perception +7
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Fiendish Restoration.** If the arcanaloth dies outside Gehenna, its body dissolves into ichor, and it gains a new body instantly and revives with all its Hit Points in Gehenna.

**Magic Resistance.** The arcanaloth has Advantage on saving throws against spells and other magical effects.

**Soul Tome.** The arcanaloth has a magic tome. While holding or carrying the tome, the arcanaloth can use its Banishing Claw action.
The tome has AC 17; HP 35; and Immunity to Necrotic, Poison, and Psychic damage. The tome regains all its Hit Points at the end of every turn, but it turns to dust if reduced to 0 Hit Points or when the arcanaloth dies. If the tome is destroyed, the arcanaloth can create a new one when it finishes a Short or Long Rest.


---

### Actions

**Multiattack.** The arcanaloth makes three Fiendish Burst attacks. It can replace one attack with a Banishing Claw attack.

**Fiendish Burst.** m,r +9, reach 5 ft. or range 120 ft. *Hit:* 31 (4d12 + 5) Necrotic damage.

**Banishing Claw (Requires Soul Tome).** m +9, reach 5 ft. *Hit:* 10 (2d4 + 5) Slashing damage plus 19 (3d12) Psychic damage. If the target is a creature, it is subjected to the following effect. cha DC 17.  The target is trapped in a demiplane inside the Soul Tome. While trapped there, the target has the Incapacitated condition. At the end of each of its turns, the target repeats the save, escaping the tome on a success. When the target escapes, it appears in the space it left or, if that space is occupied, the nearest unoccupied space.
If the target fails three of these saves while in the demiplane, it becomes bound to the tome and can escape only if the tome is reduced to 0 Hit Points.


---

### Bonus Actions

**Teleport.** The arcanaloth teleports up to 30 feet to an unoccupied space it can see.


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