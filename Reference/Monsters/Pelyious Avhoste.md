---
type: pc
race: "Humanoid (human)"
class:
 - "Pelyious Avhoste"
subClass:
 - "CR 9"
cover: "Pelyious Avhoste.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mabjov
---
###### Pelyious Avhoste
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Pelyious Avhoste.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 17 | 11 | 13 |
| **Mod** | +4 | +2 | +2 | +3 | +0 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 18
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Str +8, Dex +6
**Skills:** Perception +8, Stealth +6
**Damage Immunities:** poison; bludgeoning, piercing, slashing damage from nonmagical weapons that aren't silvered
**Condition Immunities:** poisoned

---

### Traits

**Hold Breath.** Pelyious can hold his breath for 15 minutes.


---

### Actions

**Multiattack (Humanoid or Hybrid Form).** In Humanoid form, Pelyious makes two Scimitar attacks or two Hand Crossbow attacks. In hybrid form, he can substitute one Scimitar attack for a Bite attack.

**Scimitar (Humanoid or Hybrid Form).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 7 (2d6) poison damage.

**Hand Crossbow (Humanoid or Hybrid Form).** Ranged Weapon Attack: +6 to hit, range 30/90 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 7 (2d6) poison damage.

**Bite (Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage. If the target is Medium or smaller, it is grappled (escape DC 16) and until this grapple ends, the target is restrained, and Pelyious can't Bite another target.

**Change Shape.** Pelyious polymorphs into a crocodile-humanoid hybrid, or back into his true form, which is Humanoid. His statistics are the same in each form. Any equipment he is wearing or carrying isn't transformed. He reverts to his true form if he dies.


---

### Bonus Actions

**Slippery Step (2/Day).** Pelyious teleports up to 30 feet to an unoccupied space he can see and may use Change Shape.


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