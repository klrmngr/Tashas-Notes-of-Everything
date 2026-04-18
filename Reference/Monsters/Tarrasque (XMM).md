---
type: pc
race: "Monstrosity (titan)"
class:
 - "Tarrasque"
subClass:
 - "CR 30"
cover: "Tarrasque.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/30
  - source/xmm
---
###### Tarrasque
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Tarrasque.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 30 (155,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 25 |
> | :FasHeart: HP | 697 (34d20 + 340) |
> | :FasUserGroup: Race | Monstrosity (titan) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 30 | 3 | 11 | 11 |
| **Mod** | +10 | +0 | +10 | -4 | +0 | +0 |

**Speed:** 60 ft., burrow 40 ft., climb 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 19
**Languages:** —
**Saving Throws:** Dex +9, Int +5, Wis +9, Cha +9
**Skills:** Perception +9
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; deafened; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (6/Day).** If the tarrasque fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The tarrasque has Advantage on saving throws against spells and other magical effects.

**Reflective Carapace.** If the tarrasque is targeted by a Magic Missile spell or a spell that requires a ranged attack roll, roll 1d6. On a 1-5, the tarrasque is unaffected. On a 6, the tarrasque is unaffected and reflects the spell, turning the caster into the target.

**Siege Monster.** The tarrasque deals double damage to objects and structures.


---

### Actions

**Multiattack.** The tarrasque makes one Bite attack and three other attacks, using Claw or Tail in any combination.

**Bite.** m +19, reach 15 ft. *Hit:* 36 (4d12 + 10) Piercing damage, and the target has the Grappled condition (escape DC 20). Until the grapple ends, the target has the Restrained condition and can't teleport.

**Claw.** m +19, reach 15 ft. *Hit:* 28 (4d8 + 10) Slashing damage.

**Tail.** m +19, reach 30 ft. *Hit:* 23 (3d8 + 10) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Prone condition.

**Thunderous Bellow (Recharge 5–6).** con DC 27, each creature and each object that isn't being worn or carried in a 150-foot Cone.  78 (12d12) Thunder damage, and the target has the Deafened and Frightened conditions until the end of its next turn.  Half damage only.


---

### Bonus Actions

**Swallow.** str DC 27, one Large or smaller creature Grappled by the tarrasque (it can have up to six creatures swallowed at a time).  The target is swallowed, and the Grappled condition ends. A swallowed creature has the Blinded and Restrained conditions and can't teleport, it has Total Cover against attacks and other effects outside the tarrasque, and it takes 56 (16d6) Acid damage at the start of each of the tarrasque's turns.
If the tarrasque takes 60 damage or more on a single turn from a creature inside it, the tarrasque must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the tarrasque and has the Prone condition. If the tarrasque dies, any swallowed creature no longer has the Restrained condition and can escape from the corpse using 20 feet of movement, exiting Prone.


---

### Legendary Actions

### 

**Onslaught.** The tarrasque moves up to half its Speed, and it makes one Claw or Tail attack.

**World-Shaking Movement.** The tarrasque moves up to its Speed. At the end of this movement, the tarrasque creates an instantaneous shock wave in a 60-foot Emanation originating from itself. Creatures in that area lose Concentration and, if Medium or smaller, have the Prone condition. The tarrasque can't take this action again until the start of its next turn.


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