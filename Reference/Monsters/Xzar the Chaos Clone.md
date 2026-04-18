---
type: pc
race: "Humanoid (human)"
class:
 - "Xzar the Chaos Clone"
subClass:
 - "CR 11"
cover: "Xzar the Chaos Clone.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/mabjov
---
###### Xzar the Chaos Clone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Xzar the Chaos Clone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15; 18 with mage armor |
> | :FasHeart: HP | 121 (22d8 + 22) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 12 | 20 | 10 | 12 |
| **Mod** | +1 | +3 | +1 | +5 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Common, Infernal, Primordial, Undercommon, telepathy 60 ft.
**Saving Throws:** Int +9, Wis +4
**Skills:** Arcana +13, History +13
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Chaos Phage.** Xzar's infusion with the Chaos Phage gives him the following benefits:
- Xzar regains 10 hit points at the start of his turn if he has at least 1 hit point
- Xzar has advantage on saving throws against spells and other magical effects
- Xzar has resistance to acid, cold, fire, lightning, thunder
- Xzar has darkvision and telepathy to 60 feet

**Grim Harvest (1/Turn).** When Xzar kills a creature that is neither a Construct nor Undead with a spell of 1st level or higher, Xzar regains hit points equal to twice the spell's level, or three times if it is a necromancy spell.

**No Soul.** Since Xzar doesn't have a soul, resurrection magic is able to work upon him no matter how much time has passed. For example, the revivify spell would work on Xzar even a week after he died. However, spells like true resurrection and wish are unable to bring Xzar back to life if no body exists.


---

### Actions

**Multiattack.** Xzar makes two Deprive attacks and uses Spellcasting.

**Deprive.** Melee or Ranged Spell Attack: +9 to hit, reach 5 ft., or range 120 ft., one target. *Hit:* 27 (4d10 + 5) necrotic damage.

**Death Eruption (1/Day).** Negative energy erupts from Xzar, intensified by the Chaos Phage. Any creature in a 60-foot-radius sphere around Xzar (but not including Xzar) must make a DC 17 Constitution saving throw. A creature takes 36 (8d6) necrotic damage on a failed save, or half as much damage on a successful one. A Humanoid killed by this ability rises at the start of Xzar's next turn as a zombie under his command.


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