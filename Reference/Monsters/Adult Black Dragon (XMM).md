---
type: pc
race: "Dragon (chromatic)"
class:
 - "Adult Black Dragon"
subClass:
 - "CR 14"
cover: "Adult Black Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/14
  - source/xmm
---
###### Adult Black Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Black Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Dragon (chromatic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 195 (17d12 + 85) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 21 | 14 | 13 | 19 |
| **Mod** | +6 | +2 | +5 | +2 | +1 | +4 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic
**Saving Throws:** Dex +7, Wis +6
**Skills:** Perception +11, Stealth +7
**Damage Immunities:** acid

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Melf's Acid Arrow (level 3 version).

**Rend.** m +11, reach 10 ft. *Hit:* 13 (2d6 + 6) Slashing damage plus 4 (1d8) Acid damage.

**Acid Breath (Recharge 5–6).** dex DC 18, each creature in a 60-foot-long, 5-foot-wide Line.  54 (12d8) Acid damage.  Half damage.


---

### Legendary Actions

### 

**Cloud of Insects.** dex DC 17, one creature the dragon can see within 120 feet.  22 (4d10) Poison damage, and the target has Disadvantage on saving throws to maintain Concentration until the end of its next turn.  The dragon can't take this action again until the start of its next turn.

**Frightful Presence.** The dragon uses Spellcasting to cast Fear. The dragon can't take this action again until the start of its next turn.

**Pounce.** The dragon can move up to half its Speed, and it makes one Rend attack.


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