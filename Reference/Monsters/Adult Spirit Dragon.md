---
type: pc
race: "Dragon"
class:
 - "Adult Spirit Dragon"
subClass:
 - "CR 15"
cover: "Adult Spirit Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/fraif
---
###### Adult Spirit Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Adult Spirit Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 21 | 20 | 15 | 19 |
| **Mod** | +6 | +2 | +5 | +5 | +2 | +4 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic; telepathy 120 ft.
**Saving Throws:** Dex +7, Con +10
**Skills:** History +10, Insight +7, Perception +7, Stealth +7
**Damage Resistances:** necrotic

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Time-Warping Breath or (B) Spellcasting to cast Thunderwave.

**Rend.** m +11, reach 10 ft. *Hit:* 15 (2d8 + 6) Slashing damage plus 7 (2d6) Necrotic damage.

**Ruinous Breath (Recharge 5–6).** con DC 18, each creature in a 60-foot Cone.  63 (14d8) Necrotic damage.  Half damage.

**Time-Warping Breath.** wis DC 18, each creature that isn't currently affected by this breath in a 60-foot Cone.  The target's Speed is halved, it can't take Reactions, and it can take either an action or a Bonus Action on its turn, not both. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Legendary Actions

### 

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Shattering Wave.** The dragon uses Spellcasting to cast Thunderwave.

**Unearth Ruins.** The dragon magically raises broken, ancient ruins in a 20-foot-radius, 60-foot-high Cylinder centered on a point it can see within 120 feet. Ground in the Cylinder becomes Difficult Terrain. Each creature in the Cylinder when it appears is subjected to the following effect. str DC 18.  5 (2d4) Bludgeoning damage, and the target has the Prone condition.  The dragon can't take this action again until the start of its next turn.


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