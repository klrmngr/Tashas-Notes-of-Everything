---
type: pc
race: "Dragon (chromatic)"
class:
 - "Adult Green Dragon"
subClass:
 - "CR 15"
cover: "Adult Green Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/xmm
---
###### Adult Green Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Green Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (chromatic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 21 | 18 | 15 | 18 |
| **Mod** | +6 | +1 | +5 | +4 | +2 | +4 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 22
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +7
**Skills:** Deception +9, Perception +12, Persuasion +9, Stealth +6
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Mind Spike (level 3 version).

**Rend.** m +11, reach 10 ft. *Hit:* 15 (2d8 + 6) Slashing damage plus 7 (2d6) Poison damage.

**Poison Breath (Recharge 5–6).** con DC 18, each creature in a 60-foot Cone.  56 (16d6) Poison damage.  Half damage.


---

### Legendary Actions

### 

**Mind Invasion.** The dragon uses Spellcasting to cast Mind Spike (level 3 version).

**Noxious Miasma.** con DC 17, each creature in a 20-foot-radius Sphere centered on a point the dragon can see within 90 feet.  7 (2d6) Poison damage, and the target takes a -2 penalty to AC until the end of its next turn.  The dragon can't take this action again until the start of its next turn.

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