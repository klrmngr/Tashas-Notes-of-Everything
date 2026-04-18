---
type: pc
race: "Undead"
class:
 - "Vampire Neonate"
subClass:
 - "CR 5"
cover: "Vampire Neonate.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/psi
---
###### Vampire Neonate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSI
___

> [!infobox|no-t right]
> ![[Vampire Neonate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | PSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 16 | 11 | 10 | 12 |
| **Mod** | +3 | +3 | +3 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Saving Throws:** Dex +6, Wis +3
**Skills:** Perception +3, Stealth +6
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks not made with living wood weapons

---

### Traits

**Regeneration.** The vampire regains 10 hit points at the start of its turn if it has at least 1 hit point. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of the vampire's next turn.


---

### Actions

**Multiattack.** The vampire makes two attacks, only one of which can be a bite attack.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 8 (2d4 + 3) slashing damage. Instead of dealing damage, the vampire can grapple the target (escape DC 13).

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one willing creature, or a creature that is grappled by the vampire, incapacitated, or restrained. *Hit:* 6 (1d6 + 3) piercing damage plus 7 (2d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Vampiric Glamer.** The vampire obscures its form with mind-affecting magic that makes others perceive it as a beautiful human of the same size and shape. The illusion ends if the vampire takes a bonus action to end it or if the vampire dies. A creature that can see the vampire can take an action to visually inspect it, ending the mental effect on itself and seeing the vampire's true form with a successful DC 20 Wisdom (Perception) check.

**Aura of Silence.** The vampire shrouds itself in a cloak of silence to a radius of 2 feet. Within that radius, the effect is the same as the silence spell.


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