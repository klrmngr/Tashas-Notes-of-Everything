---
type: pc
race: "Aberration"
class:
 - "Darkweaver"
subClass:
 - "CR 10"
cover: "Darkweaver.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/10
  - source/mpp
---
###### Darkweaver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Darkweaver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 149 (23d8 + 46) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 14 | 17 | 14 | 15 |
| **Mod** | +0 | +3 | +2 | +3 | +2 | +2 |

**Speed:** 50 ft., climb 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Abyssal, Deep Speech, telepathy 120 ft.
**Saving Throws:** Dex +7, Wis +6
**Skills:** Perception +6, Stealth +7
**Damage Resistances:** cold
**Damage Immunities:** necrotic

---

### Traits

**Shadowy Form.** While the darkweaver is in dim light or darkness, attack rolls against it are made with disadvantage unless the darkweaver has the incapacitated condition.

**Spider Climb.** The darkweaver can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Hypersensitivity.** The darkweaver takes 10 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.


---

### Actions

**Multiattack.** The darkweaver makes two Shadow Web attacks and one Bite attack. It can use Reel after any of these attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 13 (3d6 + 3) piercing damage plus 17 (5d6) necrotic damage, and if the target is a creature, the target's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Shadow Web.** Ranged Weapon Attack: +7 to hit, reach 120 ft., one creature. *Hit:* 16 (3d10) necrotic damage, and the target has the grappled condition (escape DC 15). The shadow web can be attacked and destroyed (AC 16; 20 hit points; vulnerability to radiant damage; immunity to bludgeoning, necrotic, poison, and psychic damage). The darkweaver can grapple up to six creatures at a time using its shadow web.

**Reel.** The darkweaver pulls each creature it has grappled up to 60 feet toward itself.


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