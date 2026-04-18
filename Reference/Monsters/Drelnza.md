---
type: pc
race: "Undead (vampire)"
class:
 - "Drelnza"
subClass:
 - "CR 15"
cover: "Drelnza.png"
campaign:
locations:
tags:
  - race/vampire
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/15
  - source/qftis
---
###### Drelnza
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Drelnza.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Undead (vampire) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Undead (vampire) |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 17 | 15 | 18 |
| **Mod** | +4 | +4 | +4 | +3 | +2 | +4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Abyssal, Common, Giant
**Saving Throws:** Dex +9, Int +8, Wis +7, Cha +9
**Skills:** Arcana +8, Deception +9, Perception +7
**Damage Resistances:** necrotic
**Condition Immunities:** exhaustion

---

### Traits

**Legendary Resistance (3/Day).** If Drelnza fails a saving throw, she can choose to succeed instead.

**Special Equipment.** Drelnza wields Heretic.

**Spider Climb.** Drelnza can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Hypersensitivity.** Drelnza takes 20 radiant damage when she starts her turn in sunlight. While in sunlight, she has disadvantage on attack rolls and ability checks.


---

### Actions

**Multiattack.** Drelnza makes one Bite attack and one Heretic attack.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 7 (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Drelnza regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A Humanoid slain in this way and then buried rises the following night as a vampire spawn under Drelnza's control.

**Heretic.** Melee Weapon Attack: +12 to hit, reach 5 ft. one target. *Hit:* 40 (6d10 + 7) slashing damage, and the target must succeed on a DC 17 Constitution saving throw or have the paralyzed condition until the start of Drelnza's next turn. Celestials have disadvantage on the saving throw.

**Charm.** Drelnza targets one Humanoid she can see within 30 feet of herself. The target must succeed on a DC 17 Wisdom saving throw or have the charmed condition. While charmed in this way, the target regards Drelnza as a trusted friend to be heeded and protected. The target isn't under Drelnza's control, but it takes her requests and actions in the most favorable way.
Each time Drelnza or her allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Drelnza is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.


---

### Reactions

**Move.** Immediately after a creature Drelnza can see ends its turn, Drelnza moves up to her speed without provoking opportunity attacks.

**Parry.** Drelnza adds 5 to her AC against one melee attack that would hit her. To do so, she must see the attacker and be wielding a melee weapon.


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