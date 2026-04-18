---
type: pc
race: "Undead"
class:
 - "Spectral Cloud"
subClass:
 - "CR 13"
cover: "Spectral Cloud.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/13
  - source/bgg
---
###### Spectral Cloud
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Spectral Cloud.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 189 (18d12 + 72) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 12 | 18 | 12 | 17 | 16 |
| **Mod** | +7 | +1 | +4 | +1 | +3 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Giant
**Saving Throws:** Dex +6, Cha +8
**Skills:** Perception +8
**Damage Resistances:** cold; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; thunder
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Blurred Form.** Attack rolls against the spectral cloud are made with disadvantage unless the attacker is within 15 feet of the spectral cloud or the spectral cloud is incapacitated.

**Incorporeal Movement.** The spectral cloud can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.


---

### Actions

**Multiattack.** The spectral cloud makes two Spectral Touch attacks.

**Spectral Touch.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) force damage plus 10 (3d6) necrotic damage. If the target is a creature, it must succeed on a DC 20 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.
A Humanoid slain by this attack immediately rises as a miniature spectral cloud (use the [[Specter]] stat block in the Monster Manual). The miniature spectral cloud acts as an ally of its creator but isn't under its control.

**Chilling Winds (Recharge 5–6).** The spectral cloud emits intensely cold wind in a 60-foot line that is 10 feet wide. Each creature in that area must make a DC 20 Constitution saving throw. On a failed save, a creature takes 38 (7d10) cold damage and has the incapacitated condition for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only.
If a creature's saving throw is successful or the effect ends for it, that creature is immune to this spectral cloud's Chilling Winds for the next 24 hours.


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