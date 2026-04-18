---
type: pc
race: "Undead"
class:
 - "Vladimir Horngaard"
subClass:
 - "CR 7"
cover: "Vladimir Horngaard.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/7
  - source/cos
---
###### Vladimir Horngaard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Vladimir Horngaard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 192 (16d8 + 64) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 13 | 16 | 18 |
| **Mod** | +4 | +2 | +4 | +1 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Draconic
**Saving Throws:** Str +7, Con +7, Wis +6, Cha +7
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Regeneration.** Vladimir regains 10 hit points at the start of his turn. If he takes fire or radiant damage, this trait doesn't function at the start of his next turn. Vladimir's body is destroyed only if he starts his turn with 0 hit points and doesn't regenerate.

**Rejuvenation.** When Vladimir's body is destroyed, his soul lingers. After 24 hours, the soul inhabits and animates another corpse on the same plane of existence and regains all its hit points. While the soul is bodiless, a wish spell can be used to force the soul to go to the afterlife and not return.

**Special Equipment.** Vladimir wields a +2 greatsword with a hilt sculpted to resemble silver dragon wings and a pommel shaped like a silver dragon's head clutching a black opal between its teeth. 

**Turn Immunity.** Vladimir is immune to effects that turn undead.

**Vengeful Tracker.** Vladimir knows the distance to and direction of Strahd, even if Strahd and Vladimir are on different planes of existence. If Strahd is destroyed, Vladimir knows.


---

### Actions

**Multiattack.** Vladimir makes two fist attacks or two attacks with his +2 Greatsword.

**Fist.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage. Strahd, the target of Vladimir's sworn vengeance, takes an extra 14 (4d6) bludgeoning damage. Instead of dealing damage, Vladimir can grapple the target (escape DC 14) provided the target is Large or smaller.

**Greatsword +2.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 20 (4d6 + 6) slashing damage. Against Strahd, Vladimir deals an extra 14 (4d6) slashing damage with this weapon.

**Vengeful Glare.** Vladimir can target Strahd within 30 feet provided he can see Strahd. Strahd must make a DC 15 Wisdom saving throw. On a failure, Strahd is paralyzed until Vladimir deals damage to him, or until the end of Vladimir's next turn. When the paralysis ends, Strahd is frightened of Vladimir for 1 minute. Strahd can repeat the saving throw at the end of each of his turns, with disadvantage if he can see Vladimir, ending the frightened condition on itself on a success.


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