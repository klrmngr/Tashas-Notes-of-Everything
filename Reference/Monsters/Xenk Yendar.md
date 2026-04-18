---
type: pc
race: "Humanoid (paladin)"
class:
 - "Xenk Yendar"
subClass:
 - "CR 10"
cover: "Xenk Yendar.png"
campaign:
locations:
tags:
  - race/paladin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/hat-tg
---
###### Xenk Yendar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Xenk Yendar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (paladin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 15 (half plate) |
> | :FasHeart: HP | 157 (21d8 + 63) |
> | :FasUserGroup: Race | Humanoid (paladin) |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 16 | 14 | 16 | 17 |
| **Mod** | +4 | +0 | +3 | +2 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Thayan, Undercommon
**Saving Throws:** Str +8, Cha +7
**Skills:** Athletics +8, History +6, Insight +7, Survival +7
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Aura of Protection.** Xenk and his allies within 10 feet of him have advantage on saving throws.


---

### Actions

**Multiattack.** Xenk makes three Daggersword attacks and uses Daggersword Flourish. He can replace Daggersword Flourish with Cleansing Touch if it's available.

**Daggersword.** Choose the attack that corresponds to the daggersword's current form (see Daggersword Shift below):

**Longsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands, plus 6 (1d12) radiant damage.

**Shortsword and Dagger.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 6 (1d12) radiant damage.

**Daggersword Flourish.** Choose the option that corresponds to the daggersword's current form (see Daggersword Shift below):

**Longsword.** Xenk magically detaches the longsword's blade from its hilt, launching the blade at a creature he can see within 30 feet of himself. The target must make a DC 16 Dexterity saving throw. On a failed save, the target is impaled by the blade, taking 14 (3d6 + 4) piercing damage, and is knocked prone. At the end of the current turn, the blade magically reattaches to its hilt.

**Shortsword and Dagger.** Xenk lashes out with both weapons. Each creature of his choice within 10 feet of him must make a DC 16 Dexterity throw. On a failed save, the creature takes 7 (2d6) piercing damage and has disadvantage on attack rolls until the start of Xenk's next turn. On a successful save, the creature takes half as much damage and suffers no other effect.

**Cleansing Touch (1/Day).** Xenk touches a creature within 5 feet of himself. The target magically regains 27 (6d8) hit points and gains the benefit of a lesser restoration spell.


---

### Bonus Actions

**Daggersword Shift.** Xenk changes the form of his daggersword, choosing one of the following forms: a longsword, or a shortsword in one hand and a dagger in the other.


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