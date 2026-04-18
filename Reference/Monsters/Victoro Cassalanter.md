---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Victoro Cassalanter"
subClass:
 - "CR 10"
cover: "Victoro Cassalanter.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/wdh
---
###### Victoro Cassalanter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Victoro Cassalanter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (glamoured studded leather, ring of protection) |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 13 | 14 | 16 | 17 | 18 |
| **Mod** | +1 | +1 | +2 | +3 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Draconic, Elvish, Infernal
**Saving Throws:** Con +6, Wis +7
**Skills:** History +7, Insight +7, Persuasion +8, Religion +7
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Special Equipment.** Victoro wears a ring of protection and glamoured studded leather disguised to look like fine clothing. He carries a rod of rulership shaped like a ruby-tipped cane.

**Fey Ancestry.** Victoro has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Rod of Rulership.** Victoro can use an action to present the rod and command obedience from each creature of his choice that he can see within 120 feet of him. Each target must succeed on a DC 15 Wisdom saving throw or be charmed for 8 hours by Victoro. While charmed in this way, the creature regards Victoro as its trusted leader. If harmed by Victoro or his companions, or commanded to do something contrary to its nature, a target ceases to be charmed in this way. The rod can't be used again until the next dawn.


---

### Actions

**Multiattack.** Victoro makes two attacks with his rapier.

**Rapier.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage.

**Cloak of Shadows (2/Day).** Victoro becomes invisible until the end of his next turn. He becomes visible early immediately after he attacks or casts a spell.

**Summon Devil (Recharges after 9 Days).** Victoro summons a [[Barbed Devil]]. The devil appears in an unoccupied space within 30 feet of Victoro, acts as Victoro's ally, and can't summon other devils. It remains for 1 minute, until it or Victoro dies, or until Victoro dismisses it as an action.


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