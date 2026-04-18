---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Hydroloth"
subClass:
 - "CR 9"
cover: "Hydroloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/9
  - source/mpmm
---
###### Hydroloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Hydroloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 21 | 16 | 19 | 10 | 14 |
| **Mod** | +1 | +5 | +3 | +4 | +0 | +2 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Skills:** Insight +4, Perception +4
**Damage Vulnerabilities:** fire
**Damage Resistances:** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The hydroloth can breathe air and water.

**Magic Resistance.** The hydroloth has advantage on saving throws against spells and other magical effects.

**Secure Memory.** The hydroloth is immune to the waters of the River Styx, as well as any effect that would steal or modify its memories or detect or read its thoughts.

**Watery Advantage.** While submerged in liquid, the hydroloth has advantage on attack rolls.


---

### Actions

**Multiattack.** The hydroloth makes two Bite or Claw attacks. It can replace one attack with a use of Spellcasting.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) force damage plus 9 (2d10) psychic damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target.  *Hit:* 14 (2d8 + 5) force damage plus 9 (2d10) psychic damage.

**Steal Memory (1/Day).** The hydroloth targets one creature it can see within 60 feet of it. The target takes 14 (4d6) psychic damage, and it must make a DC 16 Intelligence saving throw. On a successful save, the target becomes immune to this hydroloth's Steal Memory for 24 hours. On a failed save, the target loses all proficiencies; it can't cast spells; it can't understand language; and if its Intelligence and Charisma scores are higher than 5, they become 5. Each time the target finishes a long rest, it can repeat the saving throw, ending the effect on itself on a success. A greater restoration or remove curse spell cast on the target ends this effect early.

**Teleport.** The hydroloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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