---
type: pc
race: "Dragon (metallic)"
class:
 - "Adult Bronze Dragon"
subClass:
 - "CR 15"
cover: "Adult Bronze Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/xmm
---
###### Adult Bronze Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Bronze Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (metallic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 212 (17d12 + 102) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 23 | 16 | 15 | 20 |
| **Mod** | +7 | +0 | +6 | +3 | +2 | +5 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 22
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +7
**Skills:** Insight +7, Perception +12, Stealth +5
**Damage Immunities:** lightning

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Repulsion Breath or (B) Spellcasting to cast Guiding Bolt (level 2 version).

**Rend.** m +12, reach 10 ft. *Hit:* 16 (2d8 + 7) Slashing damage plus 5 (1d10) Lightning damage.

**Lightning Breath (Recharge 5–6).** dex DC 19, each creature in a 90-foot-long, 5-foot-wide Line.  55 (10d10) Lightning damage.  Half damage.

**Repulsion Breath.** str DC 19, each creature in a 30-foot Cone.  The target is pushed up to 60 feet straight away from the dragon and has the Prone condition.


---

### Legendary Actions

### 

**Guiding Light.** The dragon uses Spellcasting to cast Guiding Bolt (level 2 version).

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Thunderclap.** con DC 17, each creature in a 20-foot-radius Sphere centered on a point the dragon can see within 90 feet.  10 (3d6) Thunder damage, and the target has the Deafened condition until the end of its next turn.


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