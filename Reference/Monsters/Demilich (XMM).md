---
type: pc
race: "Undead"
class:
 - "Demilich"
subClass:
 - "CR 18"
cover: "Demilich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/18
  - source/xmm
---
###### Demilich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Demilich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 180 (72d4) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 20 | 10 | 20 | 17 | 20 |
| **Mod** | -5 | +5 | +0 | +5 | +3 | +5 |

**Speed:** 5 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 13
**Languages:** —
**Saving Throws:** Dex +11, Con +6, Int +11, Wis +9
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** necrotic; poison; psychic
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; prone; stunned

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the demilich fails a saving throw, it can choose to succeed instead.

**Undead Restoration.** If the demilich is destroyed, it reforms and regains all its Hit Points in 1d10 days unless a Wish spell is cast on its remains.


---

### Actions

**Multiattack.** The demilich makes three Necrotic Burst attacks.

**Necrotic Burst.** m,r +11, reach 5 ft. or range 120 ft. *Hit:* 24 (7d6) Necrotic damage.

**Howl (Recharge 5–6).** con DC 19, each creature in a 30-foot Emanation originating from the demilich.  70 (20d6) Psychic damage.  The target has the Frightened condition until the start of the demilich's next turn.


---

### Legendary Actions

### 

**Energy Drain.** con DC 19, one creature the demilich can see within 120 feet.  The target's Hit Point maximum decreases by 14 (4d6).  The demilich can't take this action again until the start of its next turn.

**Grave-Dust Flight.** The demilich flies up to its Fly Speed, shedding grave dust. Each creature within 5 feet of the demilich as it moves is targeted once by the following effect. con DC 19.  The target has the Blinded condition until the end of the demilich's next turn.  The demilich can't take this action again until the start of its next turn.

**Necrosis.** The demilich makes one Necrotic Burst attack.


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