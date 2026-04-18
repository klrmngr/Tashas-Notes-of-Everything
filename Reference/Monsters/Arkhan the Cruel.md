---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Arkhan the Cruel"
subClass:
 - "CR 16"
cover: "Arkhan the Cruel.png"
campaign:
locations:
tags:
  - race/dragonborn
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/16
  - source/bgdia
---
###### Arkhan the Cruel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Arkhan the Cruel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 23 (obsidian flint dragon plate, shield) |
> | :FasHeart: HP | 221 (26d8 + 104) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 10 | 10 | 18 |
| **Mod** | +5 | +1 | +4 | +0 | +0 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft. (can see invisible creatures out to the same range), passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Wis +5, Cha +9
**Skills:** Athletics +10, Deception +9, Intimidation +9
**Damage Resistances:** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** frightened

---

### Traits

**Aura of Hate.** While Arkhan isn't incapacitated, he and all fiends and undead within 30 feet of him deal 4 extra damage whenever they hit with a melee weapon attack (already factored into Arkhan's attacks). This extra damage is of the same type as the weapon's damage type.

**Hand of Vecna.** The Hand of Vecna has 8 charges and regains 1d4 + 4 expended charges daily at dawn. Arkhan can cast the following spells from the hand by expending the specified number of charges (spell save DC 18): finger of death (5 charges), sleep (1 charge), slow (2 charges), and teleport (3 charges).

**Special Equipment.** Arkhan wields Fane-Eater and wears a suit of Obsidian Flint Dragon Plate. The armor gives Arkhan advantage on ability checks and saving throws made to avoid or end the grappled condition on him.


---

### Actions

**Multiattack.** Arkhan makes three weapon attacks.

**Fane-Eater (Battleaxe).** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 16 (1d8 + 12) slashing damage, or 17 (1d10 + 12) slashing damage when used with two hands, plus 9 (2d8) cold damage. If the target is a creature and Arkhan rolls a 20 on the attack roll, the creature takes an extra 9 (2d8) necrotic damage, and Arkhan regains an amount of hit points equal to the necrotic damage dealt.

**Javelin.** Melee or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage, plus 4 piercing damage and 9 (2d8) cold damage if the javelin was used to make a melee attack.


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