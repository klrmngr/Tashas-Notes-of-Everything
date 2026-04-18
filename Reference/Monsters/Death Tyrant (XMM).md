---
type: pc
race: "Undead (beholder)"
class:
 - "Death Tyrant"
subClass:
 - "CR 14"
cover: "Death Tyrant.png"
campaign:
locations:
tags:
  - race/beholder
  - affinity/hostile
  - type/undead
  - size/large
  - cr/14
  - source/xmm
---
###### Death Tyrant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Death Tyrant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Undead (beholder) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 195 (26d10 + 52) |
> | :FasUserGroup: Race | Undead (beholder) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 19 | 15 | 19 |
| **Mod** | +4 | +2 | +2 | +4 | +2 | +4 |

**Speed:** 5 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 22
**Languages:** Deep Speech, Undercommon
**Saving Throws:** Con +7, Wis +7
**Skills:** Perception +12
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned; prone

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the death tyrant fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The death tyrant uses Eye Rays three times.

**Bite.** m +9, reach 5 feet. *Hit:* 13 (2d8 + 4) Piercing damage.

**Eye Rays.** The death tyrant randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll 1d10; reroll if the death tyrant has already used that ray during this turn):
- **1: Charm Ray.** wis DC 17.  13 (3d8) Psychic damage, and the target has the Charmed condition for 1 hour or until it takes damage.  Half damage only.
- **2: Paralyzing Ray.** con DC 17.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- **3: Fear Ray.** wis DC 17.  10 (3d6) Psychic damage, and the target has the Frightened condition until the end of its next turn.  Half damage only.
- **4: Slowing Ray.** con DC 17.  18 (4d8) Necrotic damage. Until the end of the target's next turn, the target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both.  Half damage only.
- **5: Enervation Ray.** con DC 17.  16 (3d10) Poison damage, and the target has the Poisoned condition until the end of its next turn. While Poisoned, the target can't regain Hit Points.  Half damage only.
- **6: Telekinetic Ray.** str DC 17 (the target succeeds automatically if it is Gargantuan).  The death tyrant moves the target up to 30 feet in any direction. The target has the Restrained condition until the start of the death tyrant's next turn or until the death tyrant has the Incapacitated condition. The death tyrant can also exert fine control on objects with this ray, such as manipulating a tool or opening a door or container.
- **7: Sleep Ray.** wis DC 17 (the target succeeds automatically if it is a Construct or an Undead).  The target has the Unconscious condition for 1 minute. The condition ends if the target takes damage or a creature within 5 feet of it takes an action to wake it.
- **8: Petrification Ray.** con DC 17. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition.
- **9: Disintegration Ray.** dex DC 17.  36 (8d8) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot Cube of it disintegrates into dust.  Half damage.  If the target is a creature and this damage reduces it to 0 Hit Points, it disintegrates into dust.
- **10: Death Ray.** dex DC 17.  55 (10d10) Necrotic damage.  Half damage.  The target dies if the ray reduces it to 0 Hit Points.


---

### Bonus Actions

**Negative Energy Cone.** The death tyrant's central eye emits an imperceptible, magical wave of negative energy in a 150-foot Cone. Creatures in that area can't regain Hit Points until the start of the death tyrant's next turn. An intact Humanoid corpse there instantly rises as a Zombie under the death tyrant's control and takes its turn immediately after the death tyrant on the same initiative count.


---

### Legendary Actions

### 

**Chomp.** The death tyrant makes two Bite attacks.

**Glare.** The death tyrant uses Eye Rays.


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