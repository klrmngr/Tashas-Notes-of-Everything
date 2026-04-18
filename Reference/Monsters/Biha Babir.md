---
type: pc
race: "Elemental (genie)"
class:
 - "Biha Babir"
subClass:
 - "CR 12"
cover: "Biha Babir.png"
campaign:
locations:
tags:
  - race/genie
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/12
  - source/fraif
---
###### Biha Babir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Biha Babir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Elemental (genie) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 229 (17d10 + 136) |
> | :FasUserGroup: Race | Elemental (genie) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 12 | 26 | 18 | 17 | 20 |
| **Mod** | +6 | +1 | +8 | +4 | +3 | +5 |

**Speed:** 30 ft., fly 60 ft., swim 90 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 17
**Languages:** Common, Primordial (Aquan)
**Saving Throws:** Dex +5, Wis +7, Cha +9
**Skills:** Deception +9, Insight +7, Perception +7, Stealth +5
**Damage Resistances:** acid; cold; lightning

---

### Traits

**Amphibious.** Biha Babir can breathe air and water.

**Elemental Restoration.** If Biha Babir dies outside the Elemental Plane of Water, her body dissolves into brine, and she gains a new body in 1d4 days, reviving with all her Hit Points somewhere on the Plane of Water.

**Legendary Resistance (3/Day).** If Biha Babir fails a saving throw, she can choose to succeed instead.

**Wishes.** Biha Babir knows the Wish spell but can cast it only on behalf of a non-genie creature who communicates a wish in a way Biha Babir can understand. If Biha Babir casts the spell for a creature, she suffers none of the spell's stress. Once Biha Babir has cast it three times, she can't do so again for 365 days.


---

### Actions

**Multiattack.** Biha Babir makes two Marine Burst attacks. She can replace one of these attacks with a Tail attack.

**Marine Burst.** m,r +10, reach 5 ft. or range 60 ft. *Hit:* 17 (2d10 + 6) Cold damage.

**Tail (Marid Form Only).** m +10, reach 15 ft. *Hit:* 13 (2d6 + 6) Bludgeoning damage, and if the target is Huge or smaller, it has the Prone condition.


---

### Bonus Actions

**Fluid Form.** Biha Babir shape-shifts into a form resembling a Beast or Humanoid that is Medium or smaller, while retaining her game statistics (other than her size), or returns to her true marid form.


---

### Legendary Actions

### 

**Misty Burst.** Biha Babir teleports to an unoccupied space she can see within 30 feet of herself and makes one Marine Burst attack.

**Whirlpool.** str DC 18, each creature in a 30-foot Emanation originating from Biha Babir.  10 (3d6) Force damage, and the target is pulled 15 feet straight toward Biha Babir.  Half damage only.  Biha Babir can't use this action again until the start of her next turn.


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