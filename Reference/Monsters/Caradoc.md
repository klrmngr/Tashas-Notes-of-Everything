---
type: pc
race: "Undead"
class:
 - "Caradoc"
subClass:
 - "CR 8"
cover: "Caradoc.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/8
  - source/dsotdq
---
###### Caradoc
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Caradoc.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 110 (20d8 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 18 | 12 | 15 | 13 | 19 |
| **Mod** | -5 | +4 | +1 | +2 | +1 | +4 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Solamnic
**Saving Throws:** Int +5, Wis +4
**Skills:** Deception +7, Insight +4, Perception +4
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Bound Haunting.** Caradoc's spirit is bound to Dargaard Keep. At the start of his turn, if he's outside the keep's walls and not possessing a creature using his Possession action, he must succeed on a DC 15 Charisma saving throw or vanish and reappear in an unoccupied space within the keep.

**Incorporeal Movement.** Caradoc can move through other creatures and objects as if they were difficult terrain. He takes 5 (1d10) force damage if he ends his turn inside an object.

**Rejuvenation.** If Caradoc dies, he reforms within Dargaard Keep in 2d6 days.

**Unusual Nature.** Caradoc doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** Caradoc makes two Withering Touch attacks.

**Withering Touch.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) necrotic damage.

**Possession (Recharge 5–6).** One Humanoid that Caradoc can see within 5 feet of himself must succeed on a DC 15 Charisma saving throw or be possessed by him; he then disappears, and the target is incapacitated and loses control of its body. Caradoc now controls the body but doesn't deprive the target of awareness. Caradoc can't be targeted by any attack, spell, or other effect, except ones that turn Undead, and he retains his alignment, Intelligence, Wisdom, and Charisma, immunity to being charmed and frightened, and his Divisive Whispers bonus action. He otherwise uses the possessed target's statistics but doesn't gain access to the target's knowledge, class features, or proficiencies.
The possession lasts until the body drops to 0 hit points, Caradoc ends it as a bonus action, or he is turned or forced out by an effect like the dispel evil and good spell. When the possession ends, Caradoc reappears in an unoccupied space within 5 feet of the body. The target is immune to Caradoc's Possession for 24 hours after succeeding on the saving throw or after the possession ends.


---

### Bonus Actions

**Divisive Whispers.** Caradoc magically whispers to one creature within 60 feet of himself. The target must succeed on a DC 15 Wisdom saving throw, or the target must immediately use its reaction to make a melee attack against another creature of Caradoc's choice (wasting its reaction if there are no other creatures within reach).


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