---
type: pc
race: "Giant"
class:
 - "Venom Troll"
subClass:
 - "CR 7"
cover: "Venom Troll.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/7
  - source/mpmm
---
###### Venom Troll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Venom Troll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 94 (9d10 + 45) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 20 | 7 | 9 | 7 |
| **Mod** | +4 | +1 | +5 | -2 | -1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Giant
**Skills:** Perception +2
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Poison Splash.** When the troll takes damage of any type but psychic, each creature within 5 feet of the troll takes 9 (2d8) poison damage.

**Regeneration.** The troll regains 10 hit points at the start of each of its turns. If the troll takes acid or fire damage, this trait doesn't function at the start of the troll's next turn. The troll dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The troll makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 4 (1d8) poison damage, and the creature is poisoned until the start of the troll's next turn.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 4 (1d8) poison damage.

**Venom Spray (Recharge 6).** The troll slices itself with a claw, releasing a spray of poison in a 15-foot cube. The troll takes 7 (2d6) slashing damage (this damage can't be reduced in any way). Each creature in the area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 18 (4d8) poison damage and is poisoned for 1 minute. On a successful save, the creature takes half as much damage and isn't poisoned. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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