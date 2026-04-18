---
type: pc
race: "Fey"
class:
 - "Nereid"
subClass:
 - "CR 2"
cover: "Nereid.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/tftyp
---
###### Nereid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Nereid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 12 | 13 | 14 | 16 |
| **Mod** | +0 | +3 | +1 | +1 | +2 | +3 |

**Speed:** 30 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Aquan, Common, Elvish, Sylvan
**Skills:** Acrobatics +5, Nature +3, Stealth +5, Survival +4

---

### Traits

**Amphibious.** The nereid can breathe air and water.

**Aquatic Invisibility.** If immersed in water, the nereid can make itself invisible as a bonus action. It remains invisible until it leaves the water, ends the invisibility as a bonus action, or dies.

**Mantle Dependent.** The nereid wears a mantle of silky cloth the color of sea foam, which holds the creature's spirit. The mantle has an AC and hit points equal to that of the nereid, but the garment can't be directly harmed while the nereid wears it. If the mantle is destroyed, the nereid becomes poisoned and dies within 1 hour. A nereid is willing to do anything in its power to recover the mantle if it is stolen, including serving the thief.

**Shape Water.** The nereid can cast control water at will, requiring no components. Its spellcasting ability for it is Charisma. This use of the spell has a range of 30 feet and can affect a cube of water no larger than 30 feet on a side.

**Speak With Animals.** The nereid can comprehend and verbally communicate with beasts.


---

### Actions

**Blinding Acid.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft., one target. *Hit:* 16 (2d12 + 3) acid damage, and the target is blinded until the start of the nereid's next turn.

**Drowning Kiss (Recharge 5–6).** The nereid touches one creature it can see within 5 feet of it. The target must succeed on a DC 13 Constitution saving throw or take 22 (3d12 + 3) acid damage. On a failure, it also runs out of breath and can't speak for 1 minute. At the end of each of its turns, it can repeat the save, ending the effect on itself on a success.

**Water Lash.** The nereid causes a 5-foot cube of water within 60 feet of it to take a shape of its choice and strike one target it can see within 5 feet of that water. The target must make a DC 13 Strength saving throw. On a failed save, it takes 17 (4d6 + 3) bludgeoning damage, and if it is a Large or smaller creature, it is pushed up to 15 feet in a straight line or is knocked prone (nereid's choice). On a successful save, the target takes half as much damage and isn't pushed or knocked prone.


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