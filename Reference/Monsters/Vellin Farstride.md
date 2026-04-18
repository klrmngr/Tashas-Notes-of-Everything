---
type: pc
race: "Humanoid (halfling)"
class:
 - "Vellin Farstride"
subClass:
 - "CR 9"
cover: "Vellin Farstride.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/9
  - source/mabjov
---
###### Vellin Farstride
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Vellin Farstride.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 20 (studded leather, +1 shield) |
> | :FasHeart: HP | 195 (30d6 + 90) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 20 | 16 | 11 | 14 | 11 |
| **Mod** | +0 | +5 | +3 | +0 | +2 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Abyssal, Common, Halfling, Infernal, telepathy 30 ft.
**Saving Throws:** Dex +9, Wis +6
**Skills:** Deception +4, Nature +8, Perception +10, Persuasion +8, Stealth +13, Survival +10

---

### Traits

**Animal Companions.** Vellin is accompanied by Akela ([[Wolf]] with 18 hit points). Vellin can mount or dismount Akela using 5 feet of movement. While mounted, Vellin can order Akela to Dash, Disengage, and Dodge. In addition, Vellin has an [[Owl]] companion with 3 hit points. On Vellin's turn, the owl can perform a flyby on a creature of Vellin's choice. The next attack that Vellin makes against that creature has advantage.

**Brave.** Vellin has advantage on saving throws against being frightened.

**Fiend Slayer.** When Vellin hits a Fiend with a weapon attack he deals an additional 7 (2d6) radiant damage.

**Keen Hearing and Sight.** Vellin has advantage on Wisdom (Perception) checks that rely on hearing or sight.

**Special Equipment.** Vellin wields a +1 shortsword (silvered) and a +1 shield.


---

### Actions

**Multiattack.** Vellin makes three Silvered Shortsword attacks.

**Silvered Shortsword.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 9 (1d6 + 6) piercing damage.


---

### Bonus Actions

**Nimble Escape.** Vellin can take the Disengage or Hide action.


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