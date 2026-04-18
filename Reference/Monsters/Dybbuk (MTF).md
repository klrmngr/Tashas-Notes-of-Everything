---
type: pc
race: "Fiend (demon)"
class:
 - "Dybbuk"
subClass:
 - "CR 4"
cover: "Dybbuk.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/mtf
---
###### Dybbuk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Dybbuk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 19 | 16 | 16 | 15 | 14 |
| **Mod** | -2 | +4 | +3 | +3 | +2 | +2 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Abyssal, Common, telepathy 120 ft.
**Skills:** Deception +6, Intimidation +4, Perception +4
**Damage Resistances:** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The dybbuk can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Magic Resistance.** The dybbuk has advantage on saving throws against spells and other magical effects.

**Violate Corpse.** The dybbuk can use a bonus action while it is possessing a corpse to make it do something unnatural, such as vomit blood, twist its head all the way around, or cause a quadruped to move as a biped. Any beast or humanoid that sees this behavior must succeed on a DC 12 Wisdom saving throw or become frightened for 1 minute. The frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that succeeds on a saving throw against this ability is immune to Violate Corpse for 24 hours.


---

### Actions

**Tendril.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) necrotic damage. If the target is a creature, its hit point maximum is also reduced by 3 (1d6). This reduction lasts until the target finishes a short or long rest. The target dies if this effect reduces its hit point maximum to 0.

**Possess Corpse (Recharge 6).** The dybbuk disappears into an intact corpse it can see within 5 feet of it. The corpse must be Large or smaller and be that of a beast or a humanoid. The dybbuk is now effectively the possessed creature. Its type becomes undead, though it now looks alive, and it gains a number of temporary hit points equal to the corpse's hit point maximum in life.
While possessing the corpse, the dybbuk retains its hit points, alignment, Intelligence, Wisdom, Charisma, telepathy, and immunity to poison damage, exhaustion, and being charmed and frightened. It otherwise uses the possessed target's game statistics, gaining access to its knowledge and proficiencies but not its class features, if any.
The possession lasts until the temporary hit points are lost (at which point the body becomes a corpse once more) or the dybbuk ends its possession using a bonus action. When the possession ends, the dybbuk reappears in an unoccupied space within 5 feet of the corpse.


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