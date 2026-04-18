---
type: pc
race: "Dragon (metallic)"
class:
 - "Ancient Silver Dragon"
subClass:
 - "CR 23"
cover: "Ancient Silver Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/23
  - source/xmm
---
###### Ancient Silver Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Silver Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (metallic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 22 |
> | :FasHeart: HP | 468 (24d20 + 216) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 10 | 29 | 18 | 15 | 26 |
| **Mod** | +10 | +0 | +9 | +4 | +2 | +8 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic
**Saving Throws:** Dex +7, Wis +9
**Skills:** History +11, Perception +16, Stealth +7
**Damage Immunities:** cold

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast Ice Knife (level 2 version).

**Rend.** m +17, reach 15 ft. *Hit:* 19 (2d8 + 10) Slashing damage plus 9 (2d8) Cold damage.

**Cold Breath (Recharge 5–6).** con DC 24, each creature in a 90-foot Cone.  67 (15d8) Cold damage.  Half damage.

**Paralyzing Breath.** con DC 24, each creature in a 90-foot Cone. 1 The target has the Incapacitated condition until the end of its next turn, when it repeats the save. 2 The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Legendary Actions

### 

**Chill.** The dragon uses Spellcasting to cast Hold Monster. The dragon can't take this action again until the start of its next turn.

**Cold Gale.** dex DC 23, each creature in a 60-foot-long, 10-foot-wide Line.  14 (4d6) Cold damage, and the target is pushed up to 30 feet straight away from the dragon.  Half damage only.  The dragon can't take this action again until the start of its next turn.

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.


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