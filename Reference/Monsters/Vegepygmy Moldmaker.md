---
type: pc
race: "Plant"
class:
 - "Vegepygmy Moldmaker"
subClass:
 - "CR 3"
cover: "Vegepygmy Moldmaker.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/3
  - source/qftis
---
###### Vegepygmy Moldmaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Vegepygmy Moldmaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 44 (8d6 + 16) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 14 | 10 | 16 | 11 |
| **Mod** | +0 | +2 | +2 | +0 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Vegepygmy
**Saving Throws:** Int +2, Wis +5
**Skills:** Perception +5, Stealth +4
**Damage Resistances:** lightning; piercing

---

### Traits

**Plant Camouflage.** The vegepygmy has advantage on Dexterity (Stealth) checks it makes in any terrain with ample obscuring vegetation.

**Regeneration.** The vegepygmy regains 7 hit points at the start of its turn. If it takes cold, fire, or necrotic damage, this trait doesn't function at the start of the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The vegepygmy makes two Claw attacks.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 12 (3d6 + 2) slashing damage.

**Toxic Mold (2/Day).** The vegepygmy targets a creature it can see within 60 feet of itself. If the target isn't a vegepygmy, it must make a DC 13 Constitution saving throw. On a failed save, the target takes 13 (3d8) poison damage and has the blinded and deafened conditions for 1 minute as it becomes covered in a thick layer of mold. On a successful save, the target takes half as much damage only.
The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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