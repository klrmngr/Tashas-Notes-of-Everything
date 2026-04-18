---
type: pc
race: "Dragon (chromatic)"
class:
 - "Ancient Black Dragon"
subClass:
 - "CR 21"
cover: "Ancient Black Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/21
  - source/xmm
---
###### Ancient Black Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Black Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (chromatic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 22 |
> | :FasHeart: HP | 367 (21d20 + 147) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 25 | 16 | 15 | 22 |
| **Mod** | +8 | +2 | +7 | +3 | +2 | +6 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic
**Saving Throws:** Dex +9, Wis +9
**Skills:** Perception +16, Stealth +9
**Damage Immunities:** acid

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Melf's Acid Arrow (level 4 version).

**Rend.** m +15, reach 15 ft. *Hit:* 17 (2d8 + 8) Slashing damage plus 9 (2d8) Acid damage.

**Acid Breath (Recharge 5–6).** dex DC 22, each creature in a 90-foot-long, 10-foot-wide Line.  67 (15d8) Acid damage.  Half damage.


---

### Legendary Actions

### 

**Cloud of Insects.** dex DC 21, one creature the dragon can see within 120 feet.  33 (6d10) Poison damage, and the target has Disadvantage on saving throws to maintain Concentration until the end of its next turn.  The dragon can't take this action again until the start of its next turn.

**Frightful Presence.** The dragon uses Spellcasting to cast Fear. The dragon can't take this action again until the start of its next turn.

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