---
type: pc
race: "Monstrosity"
class:
 - "Kyrilla, Accursed Gorgon"
subClass:
 - "CR 10"
cover: "Kyrilla, Accursed Gorgon.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/10
  - source/aitfr-dn
---
###### Kyrilla, Accursed Gorgon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-DN
___

> [!infobox|no-t right]
> ![[Kyrilla, Accursed Gorgon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | AitFR-DN |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 14 | 14 | 15 |
| **Mod** | +0 | +3 | +3 | +2 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Draconic, Primordial
**Saving Throws:** Wis +6, Cha +6
**Skills:** Deception +6, Insight +6, Perception +6, Stealth +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed

---

### Traits

**Feed on Pain (2/Day).** The first time she hits with a weapon attack on her turn, Kyrilla can deal an extra 16 (3d10) poison damage to the target and regains a number of hit points equal to half the damage dealt.

**Legendary Resistance (2/Day).** If she fails a saving throw, Kyrilla can choose to succeed instead.

**Petrifying Gaze.** When a creature that can see Kyrilla's eyes starts its turn within 30 feet of her, Kyrilla can force it to make a DC 14 Constitution saving throw if Kyrilla isn't incapacitated and can see the creature. If the saving throw fails by 5 or more, the creature is instantly petrified. Otherwise, a creature that fails the save begins to turn to stone and is restrained. The restrained creature must repeat the saving throw at the end of its next turn, becoming petrified on a failure or ending the effect on a success. The petrification lasts until the creature is freed by the greater restoration spell or other magic.
Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see Kyrilla until the start of its next turn, when it can avert its eyes again. If the creature looks at Kyrilla in the meantime, it must immediately make the save.
Kyrilla's accursed gaze does not affect undead or constructs. If Kyrilla sees herself reflected on a polished surface within 30 feet of her and in an area of bright light, she is, due to her curse, affected by her own gaze.

**Sunlight Sensitivity.** While in sunlight, Kyrilla has disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Kyrilla makes one attack to constrict and two attacks with her claws, or she makes three attacks with her longbow.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (3d6 + 3) slashing damage.

**Constrict.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 10 (3d6) bludgeoning damage, and the target is grappled (escape DC 13) if it is a Large or smaller creature. Until this grapple ends, the target is restrained, and Kyrilla can't constrict another target.

**Longbow.** Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. *Hit:* 16 (3d8 + 3) piercing damage.

**Summon Swarm of Poisonous Snakes (Recharge 5–6).** Kyrilla conjures a swarm of poisonous snakes into an empty space within 10 feet of her. The swarm is under Kyrilla's control and acts on her turn, immediately after her in the initiative order.
It remains in existence for up to 1 hour. She can summon no more than three swarms per day. Kyrilla can banish any or all of her summoned swarms with a bonus action.


---

### Legendary Actions

### 

**Claw.** Kyrilla or a swarm of poisonous snakes makes a weapon attack.

**Detect.** Kyrilla makes a Wisdom (Perception) check.

**Slither.** Kyrilla moves up to her speed without provoking opportunity attacks.


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