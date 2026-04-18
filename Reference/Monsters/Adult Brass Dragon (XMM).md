---
type: pc
race: "Dragon (metallic)"
class:
 - "Adult Brass Dragon"
subClass:
 - "CR 13"
cover: "Adult Brass Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/13
  - source/xmm
---
###### Adult Brass Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Brass Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (metallic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 14 | 13 | 17 |
| **Mod** | +6 | +0 | +5 | +2 | +1 | +3 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +6
**Skills:** History +7, Perception +11, Persuasion +8, Stealth +5
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Sleep Breath or (B) Spellcasting to cast Scorching Ray.

**Rend.** m +11, reach 10 ft. *Hit:* 17 (2d10 + 6) Slashing damage plus 4 (1d8) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 18, each creature in a 60-foot-long, 5-foot-wide Line.  45 (10d8) Fire damage.  Half damage.

**Sleep Breath.** con DC 18, each creature in a 60-foot Cone.  The target has the Incapacitated condition until the end of its next turn, at which point it repeats the save. 2 The target has the Unconscious condition for 10 minutes. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.


---

### Legendary Actions

### 

**Blazing Light.** The dragon uses Spellcasting to cast Scorching Ray.

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Scorching Sands.** dex DC 16, one creature the dragon can see within 120 feet.  27 (6d8) Fire damage, and the target's Speed is halved until the end of its next turn.  The dragon can't take this action again until the start of its next turn.


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