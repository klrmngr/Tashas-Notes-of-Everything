---
type: pc
race: "Construct"
class:
 - "Tomb Tapper"
subClass:
 - "CR 10"
cover: "Tomb Tapper.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/10
  - source/idrotf
---
###### Tomb Tapper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Tomb Tapper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 21 | 14 | 14 | 11 |
| **Mod** | +6 | +0 | +5 | +2 | +2 | +0 |

**Speed:** 30 ft., burrow 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 240 ft. (blind beyond this radius), passive Perception 16
**Languages:** understands Common and Undercommon but doesn't speak, telepathy 60 ft.
**Skills:** Perception +6
**Damage Resistances:** lightning
**Damage Immunities:** cold; fire
**Condition Immunities:** charmed; frightened

---

### Traits

**Petrified Death.** A tomb tapper reduced to 0 hit points turns into a lifeless stone statue. Anything it's wearing or carrying is not transformed.

**Sense Magic.** The tomb tapper senses magic within 30 feet of it and can use an action to pinpoint the location of any creature, object, or area in that range that bears magic. This sense penetrates barriers but is blocked by a thin sheet of lead.

**Tunneler.** The tomb tapper can burrow through solid rock at half its burrowing speed and leaves a 10-foot-wide, 20-foot-tall tunnel in its wake.

**Unusual Nature.** The tomb tapper doesn't require air or sleep.


---

### Actions

**Multiattack.** The tomb tapper makes two melee attacks with its sledgehammer or with its claws. If it hits the same creature with both claws, it can pull that creature within 5 feet of its mouth and make a bite attack against it.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) slashing damage.

**Claw.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) slashing damage.

**Sledgehammer.** Melee or Ranged Weapon Attack: +10 to hit, reach 15 ft. or range 30/120 ft., one target. *Hit:* 27 (6d6 + 6) bludgeoning or force damage (tomb tapper's choice). If thrown, the hammer returns to the tomb tapper at the end of its turn, landing at the tomb tapper's feet if it doesn't have a hand free to catch the weapon.


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