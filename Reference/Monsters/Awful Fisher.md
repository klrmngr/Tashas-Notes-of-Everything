---
type: pc
race: "Monstrosity"
class:
 - "Awful Fisher"
subClass:
 - "CR 18"
cover: "Awful Fisher.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/18
  - source/coa
---
###### Awful Fisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Awful Fisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 348 (24d20 + 96) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 18 | 5 | 10 | 8 |
| **Mod** | +6 | +3 | +4 | -3 | +0 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., darkvision 60 ft., passive Perception 16
**Languages:** —
**Saving Throws:** Dex +9, Con +10
**Skills:** Perception +6, Stealth +9, Survival +6

---

### Traits

**Flammable Blood.** If the fisher drops below 200 hit points, it gains vulnerability to fire damage.

**Legendary Resistance (3/Day).** If the fisher fails a saving throw, it can choose to succeed instead.

**Spider Climb.** The fisher can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The fisher makes two Claw attacks.

**Claw.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 20 (4d6 + 6) slashing damage.

**Retract Filament.** One Huge or smaller creature grappled by the fisher's Adhesive Filament must make a DC 20 Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the fisher, and the fisher makes one Claw attack against it with advantage. Anyone else who was attached to the filament is released. Until the grapple ends on the target, the fisher can't use Adhesive Filament.


---

### Bonus Actions

**Adhesive Filament.** The fisher extends a sticky filament up to 90 feet in a straight line, which adheres to anything that touches it. A Huge or smaller creature the filament adheres to has the grappled condition (escape DC 20), and ability checks made to escape this grapple have disadvantage. The filament can be attacked (AC 16; 25 hit points; immunity to poison and psychic damage). A weapon that fails to sever it becomes stuck to it, requiring an action and a successful DC 20 Strength check to pull free. Destroying the filament deals no damage to the fisher. The filament crumbles away if the fisher takes this bonus action again.


---

### Legendary Actions

### 

**Slash.** The fisher makes a Claw attack.

**Spit.** The fisher uses Adhesive Filament.

**Reel In.** The fisher uses Retract Filament.


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