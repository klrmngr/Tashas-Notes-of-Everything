---
type: pc
race: "Giant"
class:
 - "Frost Giant of Evil Water"
subClass:
 - "CR 11"
cover: "Frost Giant of Evil Water.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/11
  - source/bgg
---
###### Frost Giant of Evil Water
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Frost Giant of Evil Water.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (scale mail) |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 21 | 9 | 14 | 12 |
| **Mod** | +6 | +3 | +5 | -1 | +2 | +1 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Aquan, Common, Giant
**Saving Throws:** Dex +7, Con +9, Wis +6
**Skills:** Athletics +10, Perception +6
**Damage Immunities:** cold

---

### Traits

**Amphibious.** The giant can breathe air and water.


---

### Actions

**Multiattack.** The giant makes two Battleaxe attacks and one Harpoon attack.

**Battleaxe.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 19 (3d8 + 6) slashing damage, or 22 (3d10 + 6) slashing damage if used with two hands, plus 7 (2d6) cold damage.

**Harpoon.** Ranged Weapon Attack: +7 to hit, range 50/200 ft., one creature. *Hit:* 14 (2d10 + 3) piercing damage, and the target has the grappled condition (escape DC 16). While the target is grappled this way, its speed isn't reduced, but it can't move farther from the giant. The target takes 5 (1d10) slashing damage if it escapes from the grapple or if it tries and fails. The giant can grapple only one target at a time with its harpoon.


---

### Bonus Actions

**Reel In.** The giant pulls the target grappled by its Harpoon up to 20 feet toward itself.


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