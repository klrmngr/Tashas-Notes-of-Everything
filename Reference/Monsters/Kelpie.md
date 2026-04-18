---
type: pc
race: "Plant"
class:
 - "Kelpie"
subClass:
 - "CR 4"
cover: "Kelpie.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/4
  - source/tftyp
---
###### Kelpie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Kelpie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 16 | 7 | 12 | 10 |
| **Mod** | +2 | +2 | +3 | -2 | +1 | +0 |

**Speed:** 10 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** Common, Sylvan
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** fire; bludgeoning; piercing
**Condition Immunities:** blinded; deafened; exhaustion

---

### Traits

**Amphibious.** The kelpie can breathe air and water.

**Seaweed Shape.** The kelpie can use its action to reshape its body into the form of a humanoid or beast that is Small, Medium, or Large. Its statistics are otherwise unchanged. The disguise is convincing, unless the kelpie is in bright light or the viewer is within 30 feet of it, in which case the seams between the seaweed strands are visible. The kelpie returns to its true form if takes a bonus action to do so or if it dies.

**False Appearance.** While the kelpie remains motionless in its true form, it is indistinguishable from normal seaweed.


---

### Actions

**Multiattack.** The kelpie makes two slam attacks.

**Slam.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 12).

**Drowning Hypnosis.** The kelpie chooses one humanoid it can see within 150 feet of it. If the target can see the kelpie, the target must succeed on a DC 11 Wisdom saving throw or be magically charmed while the kelpie maintains concentration, up to 10 minutes (as if concentrating on a spell). The charmed target is incapacitated, and instead of holding its breath underwater, it tries to breathe normally and immediately runs out of breath, unless it can breathe water. If the charmed target is more than 5 feet away from the kelpie, the target must move on its turn toward the kelpie by the most direct route, trying to get within 5 feet. It doesn't avoid opportunity attacks.
Before moving into damaging terrain, such as lava or a pit, and whenever it takes damage from a source other than the kelpie or drowning, the target can repeat the saving throw. A charmed target can also repeat the saving throw at the end of each of its turns. If the saving throw is successful, the effect ends on it.
A target that successfully saves is immune to this kelpie's hypnosis for the next 24 hours.


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