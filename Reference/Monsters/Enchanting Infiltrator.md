---
type: pc
race: "Fey"
class:
 - "Enchanting Infiltrator"
subClass:
 - "CR 11"
cover: "Enchanting Infiltrator.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/11
  - source/bmt
---
###### Enchanting Infiltrator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Enchanting Infiltrator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (veiled presence) |
> | :FasHeart: HP | 156 (24d8 + 48) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 20 | 15 | 20 | 16 | 18 |
| **Mod** | +0 | +5 | +2 | +5 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 17
**Languages:** Common, thieves' cant, plus any one language
**Saving Throws:** Dex +9, Int +9
**Skills:** Deception +12, Perception +7, Stealth +13
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (3/Day).** If the infiltrator fails a saving throw, it can choose to succeed instead.

**Veiled Presence.** The infiltrator's AC includes its Wisdom modifier, and the infiltrator can't be targeted by divination magic or features that would read its mind or determine its creature type.


---

### Actions

**Multiattack.** The infiltrator makes two Poison Blade attacks and can use Beguiling Whisper.

**Poison Blade.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage plus 11 (2d10) poison damage.

**Beguiling Whisper.** The infiltrator magically whispers to a creature it can see within 30 feet of itself. The target must succeed on a DC 17 Wisdom saving throw or have the stunned condition due to fear or delight (the infiltrator's choice) until the end of the target's next turn, after which the target is immune to this Beguiling Whisper for 24 hours.


---

### Reactions

**Uncanny Dodge.** When an attacker the infiltrator can see hits the infiltrator with an attack, the infiltrator halves the attack's damage against it.


---

### Legendary Actions

### 

**Cunning.** The infiltrator escapes nonmagical restraints and ends the grappled condition on itself, then moves up to its speed without provoking opportunity attacks.

**Stab (Costs 2 Actions).** The infiltrator makes one Poison Blade attack.

**Misdirecting Escape (Costs 3 Actions).** The infiltrator magically has the invisible condition and creates an illusory duplicate of itself in its space, then teleports, along with any equipment it is wearing or carrying, to an unoccupied space within 15 feet of itself. The image flings illusory blades at two creatures of the infiltrator's choice within 20 feet of the image. Each target must make a DC 17 Wisdom saving throw, taking 13 (3d8) psychic damage on a failed save, or half as much damage on a successful one. The invisibility lasts until the end of the infiltrator's next turn.


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