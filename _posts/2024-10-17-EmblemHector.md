---
#layout: default
layout: postWhite
title: "Emblem Hector - Fire Emblem Engage Primer"
subtitle: "Hector - Emblem of Strength"
date:   2024-10-17 00:00:18 -0400
categories: jekyll Cat2
permalink: "/Emblems/Hector"
backgroundcolor: 4B0082

author: "Bradley Harris"
published: true
---
 
So insure that the images show up on the GitHub Pages, you have to insert the site.baseurl below right before the /img/... stuff. 
{{ site.baseurl }}

Do this at the end because adding this disables VS Studio's ability to view images before inserting them

When you're done inserting all the images use the hector command to hector /img/ with {{ site.baseurl }}/img/

 


| ![Emblem Pic]({{ site.baseurl }}/img/hector/Hector_Emblem_Bracelet.webp) |
| ![Emblem Pic]({{ site.baseurl }}/img/hector/hector_2.webp) |

 <h1> <div class="evocation"> Embolden us, Emblem of Strength! </div> </h1>
<br>


* TOC
{:toc}





# **Introduction**
Hector is an Emblem that is similar to Ike, in that he is designed for Tanking. However, unlike Ike, Hector differentiates himself in many ways. Whereas Ike likes to be at low HP, Hector prefers staying at high HP. Lastly, Hector specialises in Enemy Phase Combat which is a rare niche in Engage which is very Player Phase focused. 


# Stat Bonuses

| **Bond Lv.** | **STR** | **DEF** | **BUILD** |
| 1 | +1 | +2 | +1 |
| 2 | +2 | +2 | +1 |
| 4 | +2 | +3 | +1 |
| 7 | +2 | +3 | +2 |
| 9 | +3 | +3 | +2 |
| 13 | +3 | +4 | +2 |
| 14 | +4 | +4 | +2 |
| 17 | +4 | +4 | +3 |
| 18 | +4 | +5 | +3 |

Wearing the Bracelet of the Brash General grants boosts to Strength, Defence, and Build making Hector good on physical units. The boost to Build, while inferior to Leif, is still noteworthy because of how it interacts with one of his Sync Skills.  

# Sync Skills

Always ensure you BOLD the name of Inheritable Sync Skills.
Sync Skills like Cleric and Dragon Vein shouldn't be bolded

| **Sync Skill** | **Bond Lv** | **Effect** |
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Quick_Riposte2B_Icon.webp) <br> **Quick Riposte** | 1 | If Unit’s HP is 80% or more and foe initiates combat, unit will always follow up (if weapon allows). | 
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Adaptability_Icon.webp) <br> **Adaptability** | 3 | When hit by a foe’s attack, grants DEF+2 for a physical attack or RES+2 for a magical attack after combat. Lasts until end of battle, or until activated again. |
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Heavy_Attack_Icon.webp) <br> **Heavy Attack** | 8 | When making a physical attack, if an equipped weapon’s Weight exceeds Unit’s BUILD, adds excess as damage. (MAX +5) |
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Piercing_Glare_Icon.webp) <br> Piercing Glare | 12 | Use when HP is full to consume 20% of max HP and prevent foes from entering the 4 spaces diagonally adjacent to unit for 1 turn. |
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Quick_Riposte2B_Icon.webp) <br> **Quick Riposte+** | 16 | If Unit’s HP is 60% or more and foe initiates combat, unit will always follow up (if weapon allows). | 
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Adaptability2B_Icon.webp) <br> **Adaptability+** | 19 | When hit by a foe’s attack, grants DEF+3 for a physical attack or RES+3 for a magical attack after combat. Lasts until end of battle, or until activated again. |

<details>
<summary> Explanation </summary>

<b>Quick Riposte/Quick Riposte+</b> is Hector's signature Sync Skill for as long as you're above a certain HP threshold, you will always double attack on the Enemy Phase (assuming you aren't using a weapon that can't double like Thunder or a Smash Weapon). Quick Riposte is fantastic on low-speed units like Knights and Generals as with their bulk and defenses, meeting the HP threshold for this skill won't be much of an issue. One quick thing to note is that if the enemy attacks you and has a 5-point Speed advantage over you, then BOTH you and the enemy will attack twice during combat, assuming Quick Riposte activates. <br><br>

<b>Adaptability/Adaptability+</b> is a nice skill to have as the DEF/RES lasts the entire battle. Keep in mind that only one of the two buffs can be active at any given time. So if you're attacked by a physical attack, you'll receive the DEF buff but if you're attacked by magic afterward, that DEF buff turns into a RES buff. <br><br>

<b>Heavy Attack</b> is a weird Sync Skill. It encourages you to wield weapons that far exceed your weight class for extra damage. However, there are problems with this. 1) The damage boost caps out at +5 which is nice but oftentimes, you'll find yourself doing more damage with a lighter weapon that allows you double attack since you won't suffer a Speed penalty. 2) Simply wearing Hector's Bracelet increases your Build which causes some anti-synergy with this skill. To get around this, it's a good idea to have someone inherit Heavy Attack.<br><br>

<b>Piercing Glare</b> is another unique Sync Skill as it's not Inheritable like Micaiah's Cleric and Corrin's Dragon Vein. This creates terrain in an X pattern of lightning around Hector's bearer that enemies cannot pass through (See Diagram Below). This skill is incredibly versatile. You can use it to block off enemies from advancing toward you, protect vulnerable allies, or even create a chokepoint. The sky's the limit with this skill. Lastly, while the enemy cannot cross the spaces affected by Piercing Glare, your units can move through them without any problem. You can combine this with units that have Canter for some Hit-and-Run strategies. 

<table>

<tr>
    <td> <img src="{{ site.baseurl }}/img/hector/piercing-glare.PNG" alt="Description of image"> </td>
</tr>

</table>


</details>
 
# Engage Skill

| ![Pic]({{ site.baseurl }}/img/hector/FE17_Impenetrable_Icon.webp) <br> **Impenetrable** | If foe initiates combat, grants DEF/RES+30% during combat.|


|**Unit Type**|**Bonus**|
|Dragon| Critical Avoid+50 |
|Cavalry| Grants Freeze Immunity |
|Armored| DEF+50% instead of 30% |
|Flying| RES+50% instead of 30% |

<details>
<summary> Explanation </summary>

<b>Impenetrable</b> is similar to Ike's Laguz Friend as they both make their respective bearers more durable. That 30% boost to DED and RES can be great on bulky characters to make them even better tanks on the Enemy Phase. From my experience, Impenetrable's boost to Resistance can help patch up Armoured Unit's weakness to Magic. <br><br>

The Class Bonuses are all about making certain classes even more durable. Dragons get a Critical Avoid boost so large that in practice, it makes them immune to enemy Critical Hits. Cavalry Units gain immunity to Freeze which is the same as Sigurd's Headlong Rush while Armored and Flying Units gain stronger boosts to DEF and RES respectively. <br><br>

Impenetrable helps make Hector's bearer great on the Enemy Phase which is great as his Engage Attack is specifically designed for the Enemy Phase. However, this Engage Skill can be an example of "Suffering from Success". On <b>Maddening Difficulty</b>, the Enemy AI is programmed to ignore units they cannot damage (Whether an ally's DEF or RES is higher than an Enemy's Attack or an ally has so much Avoid the enemy's Accuracy is 0) and will attack your other units. So if you're not careful, Impenetrable can work against you on Maddening Difficulty. 

</details>

# Engage Attack

| ![Pic]({{ site.baseurl }}/img/hector/FE17_Storms_Eye_Icon.webp) <br> **Storm's Eye**  | Grants Break Immunity. Unit always Double Attacks. Foe cannot Double Attack. Lasts 1 turn. Sword/Axe only. |
| ![Pic]({{ site.baseurl }}/img/hector/FE17_Storms_Eye_Icon.webp) <br> **Storm's Eye+**  | <b>If Lyn is Adjacent</b>. <br> Grants Break Immunity. Unit Strikes First and always Double Attacks. Foe cannot Double Attack. Lasts 1 turn. Sword/Axe only. |


|**Unit Type**|**Bonus**|
|Dragon |Prevents 1 Critical Hit |
|Backup |Crit+20 |
|Covert |Avoid+30 |

<details>
<summary> Explanation </summary>

<b>Storm's Eye</b> (like Ike's Great Aether) is designed for the Enemy Phase. To get the most value from this Engage Attack, you should rush into a horde of enemies and dig in for the incoming Enemy Phase. Having Break immunity means that you'll always counterattack the enemy and Storm's Eye denying enemies the ability to double attack adds even more bulk to Hector's wearer. <br><br>

If an ally wearing Lyn's Ring is adjacent to Hector, then Storm's Eye+ adds Vantage to the mix where you will always strike first, regardless of your current HP. However, this is an issue with Storms Eye+ as whoever is wearing Lyn's Ring will most likely be a more appealing target for enemies. This is especially true on Maddening Difficulty as the Enemy AI is specifically programmed to not target units they cannot damage. With the DEF and RES boost (and Avoid Boost for Covert Units) from Impenetrable, that increases the odds of this happening. If this happens, you'll need to prepare countermeasures to ensure the enemies target Hector's wearer. My recommendation is to use a Rescue Staff to pull Lyn's user away from Hector after Storm's Eye+ has been activated. <br><br>

For class Bonuses, Dragons already get the massive buffer against Critical Hits from Impenetrable so they don't need this. Backup Units getting Crit+20 can be good if you're running a high critical weapon like a Killing Edge or Killer Axe and Covert Units get extra Avoid which is kinda pointless since Impenetrable will boost their DEF and RES high enough that they don't need to dodge anything to survive.

</details>

# Engage Weapons 

| **Bond Lv.** | **Name** | **Might** | **Hit** | **Crit** | **Weight** | **Range** | **Effect** |
| l | ![Pic]({{ site.baseurl }}/img/hector/WolfBeilFE17Sprite.webp) <br> **Wolf Beil** | 10 | 75 | 5 | 10 | 1 |Effective: Cavalry, Armored. |
| l0 | ![Pic]({{ site.baseurl }}/img/hector/RuneswordFE17Sprite.webp) <br> **Runesword** | 12 | 65 | 0 | 11 | 1-2 |Uses Strength/2. Hits Enemy RES. Restores HP=50% of Damage Dealt. |
| l5 | ![Pic]({{ site.baseurl }}/img/hector/ArmadsFE17Sprite.webp) <br> **Armads** | 22 | 85 | 0 | 18 | 1 | DEF+5. Effective: Dragon. |

<details>
<summary> Explanation </summary>

<b>Wolf Beil</b> is a great Engage Weapon not just for its stats but also the Effectiveness Bonuses against Armored and Cavalry. Fun Fact: Like Roy's first two Engage Weapons, the Wolf Beil has the exact same stats it did in Blazing Sword. <br><br>

The <b>Runesword</b> is an odd weapon as the in-game description isn't lying to you but it isn't telling you the entire truth. It is a Magic Weapon because it targets the enemy's Resistance Stat for damage calculations, but instead of your Magic Stat, it uses half of your Strength Stat for damage calculations. The upside is that this synergizes with Quick Riposte by draining HP from the enemy to keep your HP above the activation threshold for that skill. The downside is that those unaware of this quirk may be tricked into thinking Hector has some viability on magic-focused units. <br><br>

Hector's final Engage Weapon is the iconic helicopter Axe of Thunder, <b>Armads</b>. It beats out Ike's Urvan as the strongest, non-Smash Physical weapon in Engage. Not only does it hit like a truck but it's also accurate and quite heavy to synergize with Heavy Attack. The boost to DEF piles onto the bulk Hector already gives. Lastly, unlike other Dragon Effective Weapons, I don't have an issue with Armads as the DLC Paralogues are loaded with Wyverns who are weak to this weapon. There's also the 13th Emblem's Holy Aura which affects Armads as well. <br><br>

</details>


# Skill Inheritance 

| **Bond Lv.** | **Skill** | **Effect** | **SP Cost** |
|1 | Quick Riposte <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Quick_Riposte_Icon.webp) |If Unit’s HP is 80% or more and foe initiates combat, unit will always follow up (if weapon allows). | 2000|
|2 | Strength/Defence+1 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Str_Def_2B1_Icon.webp) |Grants STR+1 and DEF+1. |700 |
|3| Adaptability <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Adaptability_Icon.webp) |When hit by a foe’s attack, grants DEF+2 for a physical attack or RES+2 for a magical attack after combat. Lasts until end of battle, or until activated again.|350 |
|4 | Axe Guard 1<br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Axe_Guard_1_Icon.webp) |If foe is equipped with an Axe, Unit takes 1 less damage during combat. |200 |
|5 |Skill Inheritance <br> ![Pic]({{ site.baseurl }}/img/skillinherit.webp) |Unit can inherit this Emblem's Skills |Auto |
|6 |Axe Proficiency <br> ![Pic]({{ site.baseurl }}/img/axeprof.PNG) |Proficiency with Axes. Required for promotion to certain Classes |Auto |
|7 |Strength/Defence+2 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Str_Def_2B2_Icon.webp) |Grants STR+2 and DEF+2.|1600 |
|8 |Heavy Attack <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Heavy_Attack_Icon.webp) | When making a physical attack, if an equipped weapon’s Weight exceeds Unit’s BUILD, adds excess as damage. (MAX +5).| 3000|
|9 |Axe Guard 2 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Axe_Guard_2_Icon.webp) |If foe is equipped with an Axe, Unit takes 2 less damage during combat.| 400 |
|11 | Strong Bond <br> ![Pic]({{ site.baseurl }}/img/skillinherit.webp)| Unit stays engaged 1 additional turns (4 Turns) |Auto |
|12 |Strength/Defence+3 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Str_Def_2B3_Icon.webp) | Grants STR+3 and DEF+3.| 4200 |
|13 |Axe Guard 3 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Axe_Guard_3_Icon.webp)  |If foe is equipped with an Axe, Unit takes 3 less damage during combat.|600 |
|14 |Strength/Defence+4 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Str_Def_2B4_Icon.webp) |Grants STR+4 and DEF+4.|6000 |
|16 |Quick Riposte+ <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Quick_Riposte2B_Icon.webp) |If Unit’s HP is 60% or more and foe initiates combat, unit will always follow up (if weapon allows).|3000 |
|17 |Axe Guard 4 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Axe_Guard_4_Icon.webp) | If foe is equipped with an Axe, Unit takes 4 less damage during combat.|800 |
|18 |Strength/Defence+5 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Str_Def_2B5_Icon.webp) |Grants STR+5 and DEF+5.|8400 |
|19 |Adaptability+ <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Adaptability2B_Icon.webp) | When hit by a foe’s attack, grants DEF+3 for a physical attack or RES+3 for a magical attack after combat. Lasts until end of battle, or until activated again.|700 |
|19 |Axe Guard 5 <br> ![Pic]({{ site.baseurl }}/img/hector/FE17_Axe_Guard_5_Icon.webp) | If foe is equipped with an Axe, Unit takes 5 less damage during combat.|1000 |
|20 | Deep Synergy <br> ![Pic]({{ site.baseurl }}/img/skillinherit.webp)| Unit's Engage Meter is shortened by one (1) step |Auto |

<details>
<summary> Explanation </summary>

Hector's Skill Inheritance leans towards the expensive end of the SP scale with some affordable options thrown in the mix. <br><br>

The main prize here is <b>Quick Riposte</b> as it is a fantastic Enemy Phase tool that allows your slower, bulkier units to double-attack consistently. However, that power comes at a steep SP cost. I only recommend units with the sheer bulk to keep themselves above the HP threshold inherit this skill.<br><br>

<b>Adaptability</b>, however, is much cheaper but still useful. While nowhere near as powerful as Quick Riposte, that boost to DEF or RES can add a bit of bulk to your units. <br><br>

<b>Heavy Attack</b> is a skill that is better off on units not Synced with Hector, especially on Lance and Axe users whose Build might not be enough to match the weight of their weapons. If you're using the character Timerra I highly recommend getting her this skill as her Build is lower than the weight of most lances, so Heavy Attack can be a positive for her. <br><br>

Hector's Stat Skill is <b>Strength/Defence+</b> and as you'd expect, any skill that directly boosts Strength or Magic is expensive to inherit, especially at higher levels. <br><br>

Hector's Guard Skill is (fittingly) <b>Axe Guard</b>. I find Axe Guard one of the more useful Guard Skills as enemy Axe wielders like Warriors, Berserkers, etc. hit like freight trains, so having some way to soften the damage is nice, especially for how affordable they are, even at higher levels. <br><br>

Lastly, Hector oddly enough only provides <b>Axe Proficiency</b>. You'd think with the Runesword and the fact that Hector's promoted Great Lord class in Blazing Sword let him use Swords, he would also provide Sword Proficiency but he doesn't. 

</details>








# **Character Builds**

<details>
<summary> Omni-Counter Axe Tank </summary>

This build revolves around creating an extremely bulky Enemy Phase Tank that can counter enemies at both melee and range. You will need the following. <br><br>

* A Character with a high DEF Stat and/or DEF Growth Rate. Reclass them into a class that wields Axes at least Rank B like <b>General or Great Knight</b>. <br><br>

* A ranged Axe like a <b>Hand Axe</b> or preferably a <b>Tomahawk</b>. You want to give this weapon an <b>Engrave that increases Accuracy</b> like Leif's. <br><br>

* Have this unit inherit <b>Pair Up</b>. This will increase their sheer bulk as Chain Attacks are the main weakness of high DEF units. <br><br>

* (Optional). If your unit has accuracy issues, consider inheriting a <b>Hit+ Skill</b> from Sigurd.<br><br>

Not only will you have an incredibly bulky unit that can counter at 1-2 Range, but the Hand Axe/Tomahawk will allow you to use Storm's Eye. <br><br>

The issue with this build is that both Great Knights and Generals have mediocre RES stats, so a few hits from Mages might reduce their health below the threshold for Quick Riposte. This is an even bigger problem if the mages are using 3 Range Tomes like Thunder, Elthunder, or Thoron which you can't counter with a 2 Range Axe. Also remember that enemy Sword Users can still break Great Knights, even if they only do 1 Damage. So watch out for Sword Users. 

</details>



# **Final Thoughts** <br>
Overall, Hector is an Emblem designed for luring in Enemies and killing them on the Enemy Phase. He provides a great deal of bulk to units to ensure that they not only survive enemy attacks but retaliate with extreme prejudice. However, Hector's biggest flaw is that he's an Enemy Phase-focused Emblem. Fire Emblem Engage is a game that heavily encourages the player to be aggressive on the Player Phase. So Hector's very design as an Emblem is at odds with the very design of the game he's in. What this means is that Hector is an Emblem you will have to go out of your way to find practical use cases for him. He's not bad by any means, but he can feel a bit cumbersome to use at times. 