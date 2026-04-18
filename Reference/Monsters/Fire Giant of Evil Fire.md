---
type: pc
race: "Giant"
class:
 - "Fire Giant of Evil Fire"
subClass:
 - "CR 10"
cover: "Fire Giant of Evil Fire.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/10
  - source/bgg
---
###### Fire Giant of Evil Fire
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fire Giant of Evil Fire.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 150 (12d12 + 72) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 9 | 23 | 10 | 19 | 14 |
| **Mod** | +7 | -1 | +6 | +0 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Giant, Ignan
**Saving Throws:** Con +10, Wis +8, Cha +6
**Skills:** Athletics +11, Perception +8
**Damage Immunities:** fire

---

### Traits

**Shrapnel Explosion.** When the giant drops to 0 hit points, its armor explodes, destroying the giant's body and scattering the armor as shrapnel. Creatures within 10 feet of the giant when its armor explodes must make a DC 18 Dexterity saving throw, taking 21 (6d6) piercing damage on a failed save, or half as much damage on a successful one.


---

### Actions

**Multiattack.** The giant makes two Searing Scepter attacks or two Bolt of Imix attacks.

**Searing Scepter.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (3d6 + 7) bludgeoning damage plus 9 (2d8) fire damage, and the target is magically branded. While branded in this way, the target becomes visible if it's invisible, can't become invisible, and sheds dim light in a 5-foot radius. The brand disappears after 24 hours, or it can be removed from a creature or an object by any spell that ends a curse.

**Bolt of Imix.** Ranged Spell Attack: +8 to hit, range 120 ft., one target. *Hit:* 20 (3d10 + 4) fire damage, and the target must succeed on a DC 16 Wisdom saving throw or have the frightened condition until the end of the target's next turn.


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