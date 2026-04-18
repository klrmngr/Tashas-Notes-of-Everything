---
type: pc
race: "Dragon"
class:
 - "Ancient Spirit Dragon"
subClass:
 - "CR 22"
cover: "Ancient Spirit Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/22
  - source/fraif
---
###### Ancient Spirit Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Ancient Spirit Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 420 (24d20 + 168) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 25 | 24 | 18 | 23 |
| **Mod** | +8 | +2 | +7 | +7 | +4 | +6 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic; telepathy 120 ft.
**Saving Throws:** Dex +9, Con +14
**Skills:** History +14, Insight +11, Perception +11, Stealth +9
**Damage Resistances:** necrotic

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Time-Warping Breath or (B) Spellcasting to cast Thunderwave (level 2 version).

**Rend.** m +15, reach 15 ft. *Hit:* 19 (2d10 + 8) Slashing damage plus 9 (2d8) Necrotic damage.

**Ruinous Breath (Recharge 5–6).** con DC 22, each creature in a 90-foot Cone.  72 (16d8) Necrotic damage.  Half damage.

**Time-Warping Breath.** wis DC 22, each creature that isn't currently affected by this breath in a 90-foot Cone.  The target's Speed is halved, it can't take Reactions, and it can take either an action or a Bonus Action on its turn, not both. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Legendary Actions

### 

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Shattering Wave.** The dragon uses Spellcasting to cast Thunderwave (level 2 version).

**Unearth Ruins.** The dragon magically raises broken, ancient ruins in a 20-foot-radius, 60-foot-high Cylinder centered on a point it can see within 120 feet. Ground in the Cylinder becomes Difficult Terrain. Each creature in the Cylinder when it appears is subjected to the following effect. str DC 22.  13 (3d8) Bludgeoning damage, and the target has the Prone condition.  The dragon can't take this action again until the start of its next turn.


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