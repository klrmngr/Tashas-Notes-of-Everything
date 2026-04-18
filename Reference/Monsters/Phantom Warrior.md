---
type: pc
race: "Undead"
class:
 - "Phantom Warrior"
subClass:
 - "CR 3"
cover: "Phantom Warrior.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/cos
---
###### Phantom Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Phantom Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 16 | 8 | 10 | 15 |
| **Mod** | +3 | +0 | +3 | -1 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** any languages it knew in life
**Skills:** Perception +2, Stealth +4
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Ethereal Sight.** The phantom warrior can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

**Incorporeal Movement.** The phantom warrior can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Spectral Armor and Shield.** The phantom warrior's AC accounts for its spectral armor and shield.


---

### Actions

**Multiattack.** The phantom warrior makes two attacks with its spectral longsword.

**Spectral Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) force damage.

**Etherealness.** The phantom warrior enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.


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