---
type: pc
race: "Dragon (metallic)"
class:
 - "Ancient Brass Dragon"
subClass:
 - "CR 20"
cover: "Ancient Brass Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/20
  - source/xmm
---
###### Ancient Brass Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Brass Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (metallic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 332 (19d20 + 133) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 25 | 16 | 15 | 22 |
| **Mod** | +8 | +0 | +7 | +3 | +2 | +6 |

**Speed:** 40 ft., burrow 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 24
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +8
**Skills:** History +9, Perception +14, Persuasion +12, Stealth +6
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Sleep Breath or (B) Spellcasting to cast Scorching Ray (level 3 version).

**Rend.** m +14, reach 15 ft. *Hit:* 19 (2d10 + 8) Slashing damage plus 7 (2d6) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 21, each creature in a 90-foot-long, 5-foot-wide Line.  58 (13d8) Fire damage.  Half damage.

**Sleep Breath.** con DC 21, each creature in a 90-foot Cone.  The target has the Incapacitated condition until the end of its next turn, at which point it repeats the save. 2 The target has the Unconscious condition for 10 minutes. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.


---

### Legendary Actions

### 

**Blazing Light.** The dragon uses Spellcasting to cast Scorching Ray (level 3 version).

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Scorching Sands.** dex DC 20, one creature the dragon can see within 120 feet.  36 (8d8) Fire damage, and the target's Speed is halved until the end of its next turn.  The dragon can't take this action again until the start of its next turn.


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