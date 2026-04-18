---
type: pc
race: "Fiend (demon)"
class:
 - "Yochlol"
subClass:
 - "CR 10"
cover: "Yochlol.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/10
  - source/xmm
---
###### Yochlol
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Yochlol.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 19 | 18 | 13 | 15 | 17 |
| **Mod** | +2 | +4 | +4 | +1 | +2 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Elvish, Undercommon
**Saving Throws:** Dex +8, Int +5, Wis +6, Cha +7
**Skills:** Deception +11, Insight +6
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the yochlol dies outside the Abyss, its body dissolves, and it gains a new body instantly, reviving with all its Hit Points in the Abyss.

**Magic Resistance.** The yochlol has Advantage on saving throws against spells and other magical effects.

**Spider Climb.** The yochlol can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Web Walker.** The yochlol ignores movement restrictions caused by webs.


---

### Actions

**Multiattack.** The yochlol makes two Caustic Lash attacks, and it can use Spellcasting to cast Web or Dominate Person if available.

**Caustic Lash.** m,r +8, reach 10 ft. or range 120 ft. *Hit:* 25 (6d6 + 4) Acid damage.


---

### Bonus Actions

**Shape-Shift.** The yochlol shape-shifts into a Medium Humanoid or a Medium spider or back into its true form. Its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.


---

### Reactions

**Toxic Escape.**  The yochlol is hit by an attack roll.  The yochlol halves the attack's damage to itself (round down), and it teleports to an unoccupied space it can see within 30 feet of itself. con DC 15, each creature within 5 feet of the yochlol's destination space.  The target has the Poisoned condition until the end of its next turn. While Poisoned, it has the Incapacitated condition.


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