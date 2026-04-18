---
type: pc
race: "Humanoid (human)"
class:
 - "Razerblast"
subClass:
 - "CR 5"
cover: "Razerblast.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/pota
---
###### Razerblast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Razerblast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (splint armor) |
> | :FasHeart: HP | 112 (15d8 + 75) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 16 | 9 | 10 | 13 |
| **Mod** | +3 | +0 | +3 | -1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Ignan
**Skills:** Intimidation +4, Perception +3
**Damage Immunities:** fire

---

### Traits

**Searing Armor.** The razerblast's armor is hot. Any creature grappling the razerblast or grappled by it takes 5 (1d10) fire damage at the end of that creature's turn.

**Shrapnel Explosion.** When the razerblast drops to 0 hit points, a flaming orb in its chest explodes, destroying the razerblast's body and scattering its armor as shrapnel. Creatures within 10 feet of the razerblast when it explodes must succeed on a DC 12 Dexterity saving throw, taking 21 (6d6) piercing damage on a failed save, or half as much damage on a successful one.


---

### Actions

**Multiattack.** The razerblast makes three melee attacks.

**Spear.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing damage if used with two hands to make a melee attack, plus 3 (1d6) fire damage.


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