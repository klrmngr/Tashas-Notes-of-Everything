---
type: pc
race: "Monstrosity"
class:
 - "Cave Fisher"
subClass:
 - "CR 3"
cover: "Cave Fisher.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/mpmm
---
###### Cave Fisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Cave Fisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 14 | 3 | 10 | 3 |
| **Mod** | +3 | +1 | +2 | -4 | +0 | -4 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2, Stealth +5

---

### Traits

**Flammable Blood.** If the cave fisher drops to half its hit points or fewer, it gains vulnerability to fire damage.

**Spider Climb.** The cave fisher can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The cave fisher makes two Claw attacks.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.

**Retract Filament.** One Large or smaller creature grappled by the cave fisher's Adhesive Filament must make a DC 13 Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the cave fisher, and the cave fisher makes one Claw attack against it. Anyone else who was attached to the filament is released. Until the grapple ends on the target, the cave fisher can't use Adhesive Filament.


---

### Bonus Actions

**Adhesive Filament.** The cave fisher extends a sticky filament up to 60 feet, and the filament adheres to anything that touches it. A creature the filament adheres to is grappled by the cave fisher (escape DC 13), and ability checks made to escape this grapple have disadvantage. The filament can be attacked (AC 15; 5 hit points; immunity to poison and psychic damage). A weapon that fails to sever it becomes stuck to it, requiring an action and a successful DC 13 Strength check to pull free. Destroying the filament deals no damage to the cave fisher. The filament crumbles away if the cave fisher takes this bonus action again.


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