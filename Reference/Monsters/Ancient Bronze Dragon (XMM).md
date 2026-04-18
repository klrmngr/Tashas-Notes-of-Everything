---
type: pc
race: "Dragon (metallic)"
class:
 - "Ancient Bronze Dragon"
subClass:
 - "CR 22"
cover: "Ancient Bronze Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/22
  - source/xmm
---
###### Ancient Bronze Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Bronze Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (metallic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 22 |
> | :FasHeart: HP | 444 (24d20 + 192) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 10 | 27 | 18 | 17 | 25 |
| **Mod** | +9 | +0 | +8 | +4 | +3 | +7 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 27
**Languages:** Common, Draconic
**Saving Throws:** Dex +7, Wis +10
**Skills:** Insight +10, Perception +17, Stealth +7
**Damage Immunities:** lightning

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Repulsion Breath or (B) Spellcasting to cast Guiding Bolt (level 2 version).

**Rend.** m +16, reach 15 ft. *Hit:* 18 (2d8 + 9) Slashing damage plus 9 (2d8) Lightning damage.

**Lightning Breath (Recharge 5–6).** dex DC 23, each creature in a 120-foot-long, 10-foot-wide Line.  82 (15d10) Lightning damage.  Half damage.

**Repulsion Breath.** str DC 23, each creature in a 30-foot Cone.  The target is pushed up to 60 feet straight away from the dragon and has the Prone condition.


---

### Legendary Actions

### 

**Guiding Light.** The dragon uses Spellcasting to cast Guiding Bolt (level 2 version).

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Thunderclap.** con DC 22, each creature in a 20-foot-radius Sphere centered on a point the dragon can see within 120 feet.  13 (3d8) Thunder damage, and the target has the Deafened condition until the end of its next turn.


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