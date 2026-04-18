---
type: pc
race: "Undead"
class:
 - "Firegaunt"
subClass:
 - "CR 11"
cover: "Firegaunt.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/11
  - source/bgg
---
###### Firegaunt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Firegaunt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (damaged plate) |
> | :FasHeart: HP | 175 (14d12 + 84) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 7 | 23 | 10 | 14 | 13 |
| **Mod** | +7 | -2 | +6 | +0 | +2 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Giant
**Saving Throws:** Dex +2, Con +10, Cha +5
**Skills:** Athletics +11, Perception +6
**Damage Resistances:** necrotic
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Traits

**Fire Blood.** Whenever a creature within 5 feet of the firegaunt hits the firegaunt with a melee attack that deals piercing or slashing damage, that creature takes 5 (1d10) fire damage.


---

### Actions

**Multiattack.** The firegaunt makes two Heated Maul attacks.

**Heated Maul.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 23 (3d10 + 7) bludgeoning damage. The firegaunt can cause the maul to erupt with crimson flames, and the target must succeed on a DC 18 Dexterity saving throw or take 10 (3d6) fire damage and 10 (3d6) necrotic damage. The maul can erupt with flames in this way only once per turn.

**Crimson Rays (Recharge 5–6).** The firegaunt emits beams of fire from its eyes, mouth, and wounds in a 30-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking 31 (7d8) fire damage on a failed save, or half as much damage on a successful one. On a success or failure, that creature catches fire. Until the burning creature or another creature that can reach it takes an action to extinguish the fire, the burning creature can't regain hit points and takes 5 (1d10) fire damage at the start of each of its turns.


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