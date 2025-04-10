---
#layout: default
layout: post
title: "Emblem Byleth- Fire Emblem Engage Primer"
subtitle: "Byleth - Emblem of The Academy "
date:   2024-09-15 00:00:18 -0400
categories: jekyll Cat2
permalink: "/Emblems/Byleth"
backgroundcolor: B026FF
toc: true 

author: "Bradley Harris"
published: true
---

<div class = "center-image">
	<img src="{{ site.baseurl }}/img/byleth/engagebyleth.webp" alt="byleth" style="width:50%;">
</div>


 <div class="evocation"><b> Teach us, Emblem of the Academy! </b></div>
<br>

# **Introduction**
Byleth represents the 1st Switch Era Fire Emblem Game: **Three Houses**.  Byleth is simultaneously one of the most simple and complex Emblems to use. While primarily a Support Emblem, he offers decent Combat abilities to his bearer. However, out of all the Emblems in the game, Byleth's gameplay whether you choose to run him for Support or Combat, is heavily dependent on the Type of Unit wearing his ring. 

# **Initial Gameplay (Bond 1 - 10)** 

## Stat Bonuses

<div class="table-container">
    <table>
        <tr>
            <th>Bond LV.</th>  <th>MAG</th> <th>SPD</th> <th>LUCK</th>
        </tr>
        <tr>
            <td> 1</td> <td> +1</td> <td> +1</td> <td> +2</td>
        </tr>
        <tr>
            <td> 2</td> <td> +1</td> <td> +1</td> <td> +4</td>
        </tr>
        <tr>
            <td> 6</td> <td> +2</td> <td> +1</td> <td> 4</td>
        </tr>
        <tr>
            <td> 7</td> <td> +2</td> <td> +2</td> <td> 4</td>
        </tr>
        <tr>
            <td> 8</td> <td> +2</td> <td> +2</td> <td> +6</td>
        </tr>
    </table>
</div>

Wearing the Ring of the Instructor boosts **Magic, Speed**, and **Luck**. This makes Byleth lean more toward Magical Units rather than Physical ones. However, his boost to Luck is his biggest asset as it factors heavily into one of his Sync Skills. 


## Sync Skills

<div class="table-container">
    <table>
        <tr>
            <th>Sync Skill.</th> 
            <th>Bond LV.</th>
            <th>Effect</th>
        </tr>
        <tr>
            <td><img src="{{ site.baseurl }}/img/byleth/FE17_Divine_Pulse_Icon.webp" alt="Pic"><br><strong> Divine Pulse </strong></td> <!-- Sync Skill  -->
            <td> 1 </td> <!-- Bond Level  -->
            <td>May turn a missed Attack/Status Staff into a hit. <br> Trigger% = 30 + (1 * LUCK) </td> <!-- Effect  -->
        </tr>
         <tr>
            <td><img src="{{ site.baseurl }}/img/byleth/FE17_Mentorship_Icon.webp" alt="Pic"><br><strong> Mentorship </strong></td> <!-- Sync Skill  -->
            <td> 3 </td> <!-- Bond Level  -->
            <td> Grants 1.2x EXP Modifier to Unit and adjacent Allies</td> <!-- Effect  -->
        </tr>
    </table>
</div>

<details>
<summary> Explanation </summary>

<b>Divine Pulse</b> is a rather peculiar Sync Skill as there is a lot more to it than what the in-game description infers. No one seems to have concrete documentation on how this Skill works under the hood, but I'm going to take an educated guess based on my knowledge of Fire Emblem and how its calculations work. <br><br>

How Divine Pulse (likely) works is that, if the game decides that an attack will miss, this Skill will make the game roll another random number. If that random number falls within the activation range of Divine Pulse (30 + your Luck Stat), then the attack will hit its target. Better yet, <b>Divine Pulse also works with Status Staves like Freeze, Silence, Entrap, etc.</b>  For example; say Byleth's bearer has 20 Luck and their attack misses. This means that there is a 50% chance of Divine Pulse activating and making the attack connect. <br><br>

<b>In Layman's terms, think of Divine Pulse as an insurance policy against shaky hit rates from characters with mediocre Dexterity Stats but decent Luck Stats </b>. <br><br>

Thankfully, Byleth's other Sync Skill <b>Mentorship</b> is much easier to explain but no less powerful. That 20% boost to EXP gain makes Byleth great for grinding levels on not just his bearer, but anyone standing next to him. What's even better is <b>this EXP multiplier stacks with the EXP boost from Marth's Mercurius and Lucina's Parthia</b>. <br><br>

Byleth enjoys standing next to people, not just for Mentorship, but also when his Engage Form is active. 


</details>
 




## Engage Skill

| ![Engage Skill Pic]({{ site.baseurl }}/img/byleth/FE17_Instruct_Icon.webp) <br> **Instruct** | Use to grant allies within 2 spaces a stat bonus based on user's Unit Type. Bonus lasts for 1 Turn. |


<div class="table-container">
    <table>
        <tr>
            <th>Unit Type.</th> 
            <th>Bonus.</th>
        </tr>
        <tr>
            <td>Dragon</td> <!-- Unit Type  -->
            <td>All seven Basic Stats +3</td>
        </tr>
        <tr>
            <td>Backup </td> <!-- Unit Type  -->
            <td>Strength +4</td>
        </tr>
        <tr>
            <td>Cavalry </td> <!-- Unit Type  -->
            <td>Dexterity +10</td>
        </tr>
        <tr>
            <td>Covert </td> <!-- Unit Type  -->
            <td>Speed +5</td>
        </tr>
        <tr>
            <td>Armored </td> <!-- Unit Type  -->
            <td>Defense +5</td>
        </tr>
        <tr>
            <td>Flying </td> <!-- Unit Type  -->
            <td>Resistance +5</td>
        </tr>
        <tr>
            <td>Mystical </td> <!-- Unit Type  -->
            <td>Magic +4</td>
        </tr>
        <tr>
            <td>Qi Adept </td> <!-- Unit Type  -->
            <td>Luck +10</td>
        </tr>
    </table>
</div>



<details>
<summary> Explanation </summary>

If you're familiar with the Rally Skills from Awakening and Fates, then <b>Instruct</b> works the same way. It simply grants a stat boost to all allies within 2 spaces. What stats get boosted depends on the Unit Type of Byleth's bearer and this gives Byleth a large degree of versatility. <br><br>

<b>The most straightforward option is Dragons who give +3 to all stats</b>, effectively making Instruct Rally Spectrum from Awakening. This makes Alear a great choice for Byleth as they lean more toward a Support role than a Combat role. Unfortunately, the stat bonuses provided by other Unit Types pale in comparison. However, don't let that stop you from playing around with the different bonuses, and seeing what fits your playstyle the best. <br><br>

The main drawback of Instruct is that, unlike Corrin's Dragon Vein which was also dependent on Unit Type, Instruct is only usable while Engaged which only lasts 4 Turns at most. It also requires you to spend your turn and like Micaiah, Byleth's turns while Engaged are better spent elsewhere, either attacking or using his amazing Engage Attack.  <br><br>


</details>

## Engage Attack

| ![Engage Attack Pic]({{ site.baseurl }}/img/byleth/FE17_Goddess_Dance_Icon.webp) <br> **Goddess Dance** |  Use to grant another action to all adjacent Allies. <br> Refreshed Allies also receive the Instruct Buff. (See previous section) |

<details>
<summary> Explanation </summary>

I'm not exaggerating when I say <b>Goddess Dance</b> is one of the best Engage Attacks in the entire game, including DLC. There is a lot of debate over which Emblem has the best Engage Attack and Byleth is usually a top contender. <br><br>

In Fire Emblem Dancers/Refreshers have been invaluable since their inception and Byleth continues this trend. If you're familiar with how Dancers worked in Genealogy of The Holy War, Goddess Dance works the exact same way. <b>It lets up to FOUR (4) members of your army have an additional action in the same turn and this can be a complete GAME CHANGER</b>. If you know what you're doing, you can get so much done in a single turn when you have 4 allies who can act twice. This can range from rushing to Villages, killing up to 8 enemies with a squad of four, to beating Bosses with multiple HP bars. The possibilities are endless. <br><br>

However, <b>the most broken thing about Goddess Dance which that game doesn't tell you or even hint about is that it REFRESHES DANCERS</b>! In other Fire Emblem Games (Mainly Heroes) Dancers/Refreshers cannot refresh other Dancers/Refreshers but Byleth bucks this trend. What this means is with clever strategy and positioning (which is made much easier with Sigurd's Canter) you can have up to SIX (6) allies getting an additional action in one turn. Here's how it works. <br>

<b> <ol>
<li>Dancer Refreshes an Ally = +1 Action</li><br>
<li>Byleth Refreshes the Dancer and 3 other Allies = +4 Actions</li><br>
<li>Dancer Refreshes another Ally = +1 Action</li><br>
<li>Total = +6 Actions.</li><br>
</ol> </b>

The base effect of Goddess Dance alone is already incredible, but as a bonus, anyone refreshed by Goddess Dance also gets the Instruct Bonus. However, this only applies to units directly adjacent to Byleth. <br><br>

If you thought Byleth couldn't get even crazier, just wait until you see his Engage Weapons. 


</details>




## Engage Weapons 

<div class="table-container">
    <table>
        <tr>
            <th>Unit Type </th>
            <th>Bond Lv.</th> 
            <th>Name</th>
            <th>Might</th>
            <th>Hit</th>
            <th>Crit</th>
            <th>Weight</th>
            <th>Range</th>
            <th>Effect</th>
        </tr>
        <tr>
            <td>Dragon</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/AymrFE17Sprite.webp" alt="Pic"><br><strong>Aymr </strong></td> <!-- Image & Name  -->
            <td>24 </td> <!-- Might  -->
            <td>60 </td><!-- Hit  -->
            <td>20 </td> <!-- Crit  -->
            <td>11 </td> <!-- Weight  -->
            <td>1 </td> <!-- Range  -->
            <td>Smash Weapon. Effective: Dragon </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>Backup</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/BlutgangFE17Sprite.webp" alt="Pic"><br><strong>Blutgang </strong></td> <!-- Image & Name  -->
            <td>8 </td> <!-- Might  -->
            <td>80 </td><!-- Hit  -->
            <td>0 </td> <!-- Crit  -->
            <td>7 </td> <!-- Weight  -->
            <td>1 </td> <!-- Range  -->
            <td>Magic Weapon. Effective: Dragon, Cavalry </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>Cavalry</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/AreadbharFE17Sprite.webp" alt="Pic"><br><strong>Areadbhar </strong></td> <!-- Image & Name  -->
            <td>14 </td> <!-- Might  -->
            <td>75 </td><!-- Hit  -->
            <td>10 </td> <!-- Crit  -->
            <td>9 </td> <!-- Weight  -->
            <td>1 </td> <!-- Range  -->
            <td>If user initiates combat; Might+50% </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>Covert</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/FailnaughtFE17Sprite.webp" alt="Pic"><br><strong>Failnaught </strong></td> <!-- Image & Name  -->
            <td>13 </td> <!-- Might  -->
            <td>75 </td><!-- Hit  -->
            <td>20 </td> <!-- Crit  -->
            <td>9 </td> <!-- Weight  -->
            <td>2-3 </td> <!-- Range  -->
            <td>If user initiates combat; Grants Avoid+20. Effective: Dragon </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>Armored</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/FE17AegisShieldSprite.webp" alt="Pic"><br><strong>Aegis Shield </strong></td> <!-- Image & Name  -->
            <td>- </td> <!-- Might  -->
            <td>- </td><!-- Hit  -->
            <td>- </td> <!-- Crit  -->
            <td>- </td> <!-- Weight  -->
            <td>- </td> <!-- Range  -->
            <td>Defense+6, Resistance+3. DEX% Chance to half damage taken. </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>Flying</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/LuinFE17Sprite.webp" alt="Pic"><br><strong> Luin </strong></td> <!-- Image & Name  -->
            <td>11 </td> <!-- Might  -->
            <td>90 </td><!-- Hit  -->
            <td>10 </td> <!-- Crit  -->
            <td>9 </td> <!-- Weight  -->
            <td>1 </td> <!-- Range  -->
            <td>+1 Damage for every 3 Speed. Effective: Dragon </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>Mystical</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/FE17ThyrsusSprite.webp" alt="Pic"><br><strong>Thyrsus </strong></td> <!-- Image & Name  -->
            <td>- </td> <!-- Might  -->
            <td>- </td><!-- Hit  -->
            <td>- </td> <!-- Crit  -->
            <td>- </td> <!-- Weight  -->
            <td>- </td> <!-- Range  -->
            <td>Magic Range+2. DEX% Chance to half damage taken. </td> <!-- Effect  -->
        </tr>               
       <tr>
            <td>Qi Adept</td>
            <td>l</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/FE17RafailGemSprite.webp" alt="Pic"><br><strong>Rafail Gem </strong></td> <!-- Image & Name  -->
            <td>- </td> <!-- Might  -->
            <td>- </td><!-- Hit  -->
            <td>- </td> <!-- Crit  -->
            <td>- </td> <!-- Weight  -->
            <td>- </td> <!-- Range  -->
            <td>Nullifies Effective Damage and Critical Hits. DEX% Chance to half damage taken. </td> <!-- Effect  -->
        </tr>
        <tr>
            <td>All</td>
            <td>l0</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/VajraMushtiFE17Sprite.webp" alt="Pic"><br><strong>Vajra-Mushti </strong></td> <!-- Image & Name  -->
            <td>5 </td> <!-- Might  -->
            <td>90 </td><!-- Hit  -->
            <td>10 </td> <!-- Crit  -->
            <td>7 </td> <!-- Weight  -->
            <td>1 </td> <!-- Range  -->
            <td>If user initiates combat, attacks twice. Uses lower of Foe's DEF/RES for Damage Calculations. </td> <!-- Effect  -->
        </tr> 
    </table>
</div>

<details>
<summary> Explanation </summary>

When Byleth saw Leif, Eirika, and Corrin rocking 4 Engage Weapons instead of 3, he said "Pfft, Amateurs.". <b>At Bond 1, every single Unit Type in the game gets a different Engage Weapon or Item from Byleth</b>. This is another big reason Byleth's gameplay is heavily dependent on the type of Unit wearing his ring. <br><br>

Starting us off, <b>Dragons get Aymr</b> which is incredibly hilarious. If a certain ashen-haired emperor found out about this, she would be seething. Gameplay-wise, Aymr is a swing-and-miss as Alear in their Dragon Child/Divine Dragon Class won't have the raw Strength Stat to make good use of this. <br><br> 

<b>Backup Units get Blutgang</b> which is another dud. It's a Magical Weapon and even with Byleth's passive Magic boost, the majority of Backup Units are Physical attackers who don't have the raw Magic stat to make good use of this. Furthermore, Blutgang has worse stats than a standard Levin Sword and can't attack at range. <br><br>

<b>Cavalry Units get Areadbhar</b> (And this makes me salty that Dimitri's unique promotion in Three Houses wasn't a horse-mounted class). They get a much better deal compared to Backup Units with that +50% Might as if you're initiating combat, Areadbhar effectively has 21 Might, on par with Smash Weapons. Combine this with Sigurd's Momentum (which is good on Cavalry Units) and you could potentially one-shot enemies. <br><br>

<b>Covert Units get Failnaught</b> which is basically a Longbow on steroids. It has a good Critical Rate and and an Avoid boost which stacks with the doubled Avoid boost Covert Units get while standing in favorable terrain. <br><br>

<b>Flying Units get Luin</b> which is a decent Engage Weapon. Getting a damage boost based on Speed is more practical than you'd think as Flying Classes like Griffin Knights or Wyvern Knights have good Speed stats. <br><br>

<b>Armored Units get the Aegis Shield</b> which helps them double down on the role as Tanks. The +6 Defense is great as it adds to their already impressive bulk. However, don't expect that +3 Resistance to patch up their weakness to magic. Lastly, try not to rely on the Damage Reduction effect as Armored Units don't have the Dexterity stats to make this reliable. <br><br>

<b>Qi Adepts get the Rafail Gem</b> which is an oddball. The immunity to Critical Hits is nice as you'll often see enemies with single-digit Critical Rates getting lucky. <b>However, the immunity to Effectiveness Damage mainly applies to Alear when reclassed as Martial Monk/Master as they are always weak to Dragon Effectiveness weapons regardless of Class</b>. It's nice but dragon-slaying weapons like the Wyrmslayer are quite rare on the enemy's side. <br><br>

Unfortunately, all of these weapons pale in comparison to what Byleth gives to <b>Mystical Unit; Thyrsus</b>. This item passively boosts the range of ALL Tomes in the game. This includes Surge and Elsurge, both of which are locked to 1 Range but have infinite accuracy. Thyrsus negates the one weakness of Surge Tomes, but it doesn't stop there. Thunder Tomes have their 3 Range increased to a crazy 5 Range, making Mystical Units into long-range snipers with Thoron. With Thyrsus, Mystical Units can attack enemies from a safe distance, without fear of retaliation. <br><br>

Last but not least, <b>at Bond 10, everyone gets the Vajra-Mushti</b>. This is an Arts Weapon that calculates damage using the lower of the enemy's Defense and Resistance. It's a shame this isn't how all Arts Weapons work but this gives this weapon a nice niche. 

</details>


## Engraving

<div class="table-container-engrave">
    <table>
        <tr>
            <th>Name</th>
            <th>Might</th>
            <th>Hit</th>
            <th>Crit</th>
            <th>Weight</th>
            <th>Avoid</th>
            <th>Dodge</th>
        </tr>
        <tr>
            <td><img src="{{ site.baseurl }}/img/byleth/Engrave-Byleth.png" alt="Pic"><br><strong>Academy Engrave</strong></td> <!-- Image & Name  -->
            <td>- </td> <!-- Might  -->
            <td>+30 </td><!-- Hit  -->
            <td>+10 </td> <!-- Crit  -->
            <td>+2 </td> <!-- Weight  -->
            <td>+10 </td> <!-- Avoid  -->
            <td>+30 </td> <!-- Dodge  -->
        </tr>
    </table>
</div>

<details>
<summary> Explanation </summary>

Byleth's <b>Academy Engrave</b> is similar to Lucina's Awakening Engrave. It's great for fixing questionable Hit Rates, especially on Axes. That +2 Weight penalty is a pain but you should have units that can handle the extra Weight. The other bonuses are nice, but the main application of this Engrave is fixing Hit Rates. If you're using the weapons from the Fire Emblem Heroes DLC, this Engrave is viable as they are not that heavy, to begin with, and can take the +2 Weight. 

</details>


## Skill Inheritance 

<div class="table-container"> 
    <table>
        <tr>
            <th>Bond LV.</th> 
            <th>Skill.</th>
            <th>Effect</th>
            <th>SP Cost</th>
        </tr>
        <tr>
            <td>1 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Luck_2B2_Icon.webp" alt="Pic"><br>Luck+2  </td> <!-- Skill  -->
            <td>Grants Luck+2 </td> <!-- Effect  -->
            <td>100 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>1 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Divine_Pulse_Icon.webp" alt="Pic"><br>Divine Pulse  </td> <!-- Skill  -->
            <td>May turn a missed Attack/Status Staff into a hit. <br> Trigger% = 30 + (1 * LUCK)  </td> <!-- Effect  -->
            <td>250 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>2 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Luck_2B4_Icon.webp" alt="Pic"><br>Luck+4  </td> <!-- Skill  -->
            <td>Grants Luck+4 </td> <!-- Effect  -->
            <td>300 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>3 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Mentorship_Icon.webp" alt="Pic"><br> Mentorship  </td> <!-- Skill  -->
            <td>Grants 1.2x EXP Modifier to Unit and adjacent Allies </td> <!-- Effect  -->
            <td>250</td> <!-- SP Cost -->
        </tr>
         <tr>
            <td>4 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Art_Focus_1_Icon.webp" alt="Pic"><br>Arts Focus 1  </td> <!-- Skill  -->
            <td>Grants Hit+10 at a cost of Dodge-10 when using a Arts Weapon. </td> <!-- Effect  -->
            <td>100 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>5 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/skillinherit.webp " alt="Pic"><br> Skill Inheritance  </td> <!-- Skill  -->
            <td> Unit can inherit this Emblem's Skills</td> <!-- Effect  -->
            <td> Auto</td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>6 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Art_Focus_2_Icon.webp" alt="Pic"><br>Arts Focus 2  </td> <!-- Skill  -->
            <td>Grants Hit+15 at a cost of Dodge-10 when using a Arts Weapon. </td> <!-- Effect  -->
            <td>300 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td> 6</td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/artsprof.PNG" alt="Pic"><br> Arts Proficiency</td> <!-- Skill  -->
            <td>Proficiency with Arts. Required for Promotion/Reclassing to certain Classes. </td> <!-- Effect  -->
            <td>Auto </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td> 7</td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Art_Focus_3_Icon.webp" alt="Pic"><br>Arts Focus 3  </td> <!-- Skill  -->
            <td>Grants Hit+20 at a cost of Dodge-10 when using a Arts Weapon. </td> <!-- Effect  -->
            <td>500 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td> 8</td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Luck_2B6_Icon.webp" alt="Pic"><br>Luck+6  </td> <!-- Skill  -->
            <td>Grants Luck+6 </td> <!-- Effect  -->
            <td>500 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td> 9</td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/swordprof.PNG" alt="Pic"><br>Sword Proficiency    </td> <!-- Skill  -->
            <td>Proficiency with Swords. Required for Promotion/Reclassing to certain Classes.  </td> <!-- Effect  -->
            <td>Auto </td> <!-- SP Cost -->
        </tr>
    </table>
</div>

<details>
<summary> Explanation </summary>

While Byleth's Engage Weapons ranged from meh to incredible, his Skill Inheritance is much more constant and useful across the board, all at incredibly affordable prices. <br><br>

<b>Divine Pulse</b> and <b>Mentorship</b> are the main prizes here as both are incredibly well-priced for the value they bring to the table. If you're someone who likes being slightly overlevelled compared to the Enemy, then I recommend spreading Mentorship around. <br><br>

Byleth's Stat Skill is <b>Luck+</b> which synergizes extremely well with Divine Pulse. Even if you aren't using Divine Pulse on other Units, the boost to Luck is still useful as the higher a Unit's Luck is, the less likely they are to be hit by Enemy critical hits. <b>Think of the Luck+ Skills as an insurance policy against low Enemy Critical Rates</b>. <br><br>

<b>If you're planning on using Status Staves combined with Micaiah's Augment, I highly recommend them inheriting Divine Pulse</b>. Combining this skill with Staff Mastery or a Luck+ Skill will ensure your Status Staves rarely miss. <br><br>

Byleth's Weapon Skill is <b>Arts Focus</b> which, like other Focus Skills is borderline useless. Arts Weapons rarely have any issue hitting enemies because of their high base accuracy. <br><br>

For Proficiencies, Byleth grants <b>Sword Proficiency</b> which isn't anything new. Byleth's other Proficiency is his other Claim to Fame: <b>Arts Proficiency</b>. Byleth is the only Non-DLC Emblem in the entire game to grant Arts Proficiency. <b>Once you have the Ring of the Instructor, anyone in your army besides Jean, Framme, and Alear have access to Qi Adept Classes</b>. 

</details>





# **Post Paralogue Gameplay (Bond 11 - 20)** 

<div class="evocation"><b> Available after Chapter 14 </b></div>

## Stat Bonuses

<div class="table-container">
    <table>
        <tr>
            <th>Bond LV.</th>  <th>MAG</th> <th>SPD</th> <th>LUCK</th>
        </tr>
        <tr>
            <td> 12</td> <td> +3</td> <td> +2</td> <td> +6</td>
        </tr>
        <tr>
            <td> 14</td> <td> +3</td> <td> +3</td> <td> +6</td>
        </tr>
        <tr>
            <td> 16</td> <td> +3</td> <td> +3</td> <td> +8</td>
        </tr>
        <tr>
            <td> 17</td> <td> +3</td> <td> +3</td> <td> +10</td>
        </tr>
        <tr>
            <td> 19</td> <td> +3</td> <td> +3</td> <td> +12</td>
        </tr>
    </table>
</div>

Byleth's stat bonuses cap out at good but not great numbers. Luck is the exception as that <b>+12 Luck</b> at Bond 19 is incredible and goes a long way with Divine Pulse. 

## Sync Skills

<div class="table-container">
    <table>
        <tr>
            <th>Sync Skill.</th> 
            <th>Bond LV.</th>
            <th>Effect</th>
        </tr>
        <tr>
            <td><img src="{{ site.baseurl }}/img/byleth/FE17_Lost_26_Found_Icon.webp" alt="Pic"><br><strong>Lost & Found </strong></td> <!-- Sync Skill  -->
            <td> 13 </td> <!-- Bond Level  -->
            <td>If Unit finishes action next to an Ally. LUCK% chance to raise Support with that Ally. </td> <!-- Effect  -->
        </tr>
         <tr>
            <td><img src="{{ site.baseurl }}/img/byleth/FE17_Divine_Pulse2B_Icon.webp" alt="Pic"><br><strong>Divine Pulse+ </strong></td> <!-- Sync Skill  -->
            <td> 18 </td> <!-- Bond Level  -->
            <td>May turn a missed Attack/Status Staff into a hit. <br> Trigger% = 50 + (1 * LUCK)  </td> <!-- Effect  -->
        </tr>
    </table>
</div>

<details>
<summary> Explanation </summary>

<b>Lost and Found</b> is Byleth's final Sync Skill and it's more of a joke Skill than anything serious. Having a Luck-based chance of raising Support Points with allies sounds nice in theory, but in practice, it's only one (1) Support Point. You can get that guaranteed from normal gameplay like fighting adjacent to an ally or healing them with a staff. Corrin's Quality Time is more reliable than this Skill and it heals your allies. <br><br>

<b>Divine Pulse+</b> however is far from a joke. In fact, it's one of the more powerful Sync Skills in the game. It works the exact same way as its vanilla counterpart but the base activation rate is increased to 50%. In practice, what this means is that <b>if you have a character with 50+ Luck (Which isn't hard on certain characters when combined with Byleth's passive Luck boost), that means they will NEVER MISS</b> as Divine Pulse+ will have a 100% activation rate

</details>





## Engage Weapons 

<div class="table-container">
    <table>
        <tr>
            <th>Bond Lv.</th> 
            <th>Name</th>
            <th>Might</th>
            <th>Hit</th>
            <th>Crit</th>
            <th>Weight</th>
            <th>Range</th>
            <th>Effect</th>
        </tr>
        <tr>
            <td>l5</td> <!-- Bond Level  -->
            <td><img src="{{ site.baseurl }}/img/byleth/SwordoftheCreatorFE17Sprite.webp" alt="Pic"><br><strong>Sword of The Creator </strong></td> <!-- Image & Name  -->
            <td>11 </td> <!-- Might  -->
            <td>90 </td><!-- Hit  -->
            <td>10 </td> <!-- Crit  -->
            <td>7 </td> <!-- Weight  -->
            <td>1-2 </td> <!-- Range  -->
            <td>+1 Damage for every 3 Magic. Effective: Dragon </td> <!-- Effect  -->
        </tr>
    </table>
</div>

<details>
<summary> Explanation </summary>

Reaching Bond 15 with Byleth grants you the <b>Sword of the Creator</b> (or <b>Creator Sword</b> depending on who you ask). Despite the low base Might, it is still a 1-2 Range Sword that isn't too heavy and is very accurate. That bonus of adding damage based on Magic might nudge you to use this with dedicated Mages but please remember that the Creator Sword is still a Physical Weapon that calculates damage using a Unit's Strength Stat. So don't expect Magical Units to get much mileage out of this. However, some Mixed-Attacker Classes like Mage Knights, Griffin Knights, and Vidame can get some decent use out of this. 

</details>




## Skill Inheritance


<div class="table-container"> 
    <table>
        <tr>
            <th>Bond LV.</th> 
            <th>Skill.</th>
            <th>Effect</th>
            <th>SP Cost</th>
        </tr>
        <tr>
            <td>11 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/skillinherit.webp " alt="Pic"><br>Strong Bond   </td> <!-- Skill  -->
            <td>Unit stays Engaged for 1 additional Turn (4 Turns) </td> <!-- Effect  -->
            <td>Auto </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>12 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Art_Focus_4_Icon.webp" alt="Pic"><br>Arts Focus 4  </td> <!-- Skill  -->
            <td>Grants Hit+25 at a cost of Dodge-10 when using a Arts Weapon. </td> <!-- Effect  -->
            <td>700 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>13 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Lost_26_Found_Icon.webp" alt="Pic"><br> Lost & Found </td> <!-- Skill  -->
            <td> If Unit finishes action next to an Ally. LUCK% chance to raise Support with that Ally. </td> <!-- Effect  -->
            <td> 250 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>14 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Art_Focus_5_Icon.webp" alt="Pic"><br>Arts Focus 5  </td> <!-- Skill  -->
            <td>Grants Hit+30 at a cost of Dodge-10 when using a Arts Weapon. </td> <!-- Effect  -->
            <td>1000 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>16 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Luck_2B8_Icon.webp" alt="Pic"><br>Luck+8  </td> <!-- Skill  -->
            <td>Grants Luck+8 </td> <!-- Effect  -->
            <td>1000 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>17 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Luck_2B10_Icon.webp" alt="Pic"><br>Luck+10  </td> <!-- Skill  -->
            <td>Grants Luck+10 </td> <!-- Effect  -->
            <td>2000 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>18 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Divine_Pulse2B_Icon.webp" alt="Pic"><br> </td> <!-- Skill  -->
            <td>May turn a missed Attack/Status Staff into a hit. <br> Trigger% = 50 + (1 * LUCK)   </td> <!-- Effect  -->
            <td>500 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>19 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/byleth/FE17_Luck_2B12_Icon.webp" alt="Pic"><br>Luck+12  </td> <!-- Skill  -->
            <td>Grants Luck+12 </td> <!-- Effect  -->
            <td>3000 </td> <!-- SP Cost -->
        </tr>
        <tr>
            <td>20 </td> <!-- Bond Level  -->
            <td> <img src="{{ site.baseurl }}/img/skillinherit.webp" alt="Pic"><br>Deep Synergy   </td> <!-- Skill  -->
            <td>Unit's Engage Meter is shortened by one (1) step  </td> <!-- Effect  -->
            <td>Auto </td> <!-- SP Cost -->
        </tr>
    </table>
</div>

<details>
<summary> Explanation </summary>

When it comes to Byleth's higher Inheritance, <b>the higher levels of Luck+ and Divine Pulse</b> are what you're really after here. <br><br>

<b>Divine Pulse+</b> is great on most units, especially for how cheap it is. Even units with middling Luck stats in the 20-30s range can still get some great use from this Skill. The cheap 500 SP price tag is offset by the steep Bond 18 requirement, so it's a fair tradeoff. <br><br>

<b>Lost and Found</b> and <b>Arts Focus</b> are better off ignored as they are wastes of SP and a Skill Slot.

</details>



# **Character Builds**




<details>
<summary> WMD (Wand of Mass Destruction)</summary>

This is a popular build for Byleth and the one I gravitate towards the most. <b>Putting Byleth on a Mystical Unit allows them to take advantage of his passive boosts to Magic and the fact that he gives Thyrsus right from the start</b>. This turns Mystical Units into magical snipers with Tomes like Thunder, Elthunder, and Thoron. These Tomes have questionable hit rates but you have Divine Pulse as an insurance policy. <br><br>

<b>The main downside with this build is that Thyrsus is the only Engage Weapon most Mystical Units will get any real value out of</b>. The Vajra-Mushti and Creator Sword are both Physical Weapons at the end of the day and they do not synergize with the low Strength stats of Mystical Units. <br><br>

However, <b>Celine is one of the better candidates for this build</b>. Her special Noble and Vidame Classes are primarily Magical attackers but give her decent Physical capabilities as well. Furthermore, Celine's Noble and Vidame Classes have a maximum Luck Stat of 50. Celine's high Growth Rate ensures she will have very high Luck. <b>Once her Luck reaches 38, combined with the +12 Luck Byleth gives at Bond 19, Celine will have guaranteed activation of Divine Pulse+, making all of her attacks land, regardless of her accuracy</b>. 


</details>

<details>
<summary> Tutoring at the Elusian Academy</summary>

This build is similar to the WMD Build with Celine, albeit with the character <b>Hortensia</b>. Like Celine, Hortensia has a very high Luck Growth Rate and her personal Classes (Wing Tamer and Sleipnir Rider) have a maximum Luck stat of 53. <b>This build is designed around Status Staves as Divine Pulse(+) also affects Status Staves</b>. <br><br>

<b>With Byleth on Hortensia, this will guarantee your Status Staves rarely ever miss</b>. While this build doesn't have the AoE effect as Micaiah's Augment, it is still useful if you only need to debilitate one single enemy. <br><br>

This build is focused on Support as Wing Tamer and Sleipnir Rider are Flying Classes, meaning they get Luin instead of Thyrsus from Byleth. Hortensia isn't that great at combat as she focuses on her amazing Staff Utility. However, since Hortensia is a Flying Unit, it lets her more easily get into position to perform Goddess Dance as she won't be slowed down by terrain. 

</details>


<details>
<summary> Professor Alear of Lythos Academy</summary>

<b>Alear is one of the better candidates for Byleth</b>, mainly for the bonuses to Instruct and Goddess Dance they receive in their Dragon Child/Divine Dragon Classes, pushing their status as Support Unit to the limit. Combat-wise, Alear in their default class is a decent combat unit and they will get some value out of the Engage Weapons Byleth provides them. <br><br>

If your other Support Emblems (Micaiah, Lucina, Corrin) are already taken, then Byleth makes a good partner for Alear. 


</details>


<details>
<summary> You can't (Goddess) Dance on an Empty Stomach.</summary>

If you recall, <b> one of Celica's Inheritable Sunk Skills at Bond 8 is Favourite Food. This Skill maxes out a Unit's Engage Meter whenever they eat a Packed Lunch</b>. You can only have one Packed Lunch in your inventory at a time and once it's consumed, that's it until you make another one back at the Somniel. However, what if I told you there was a way to have multiple Packed Lunches in a single Chapter? <br><br>

Enter the character <b>Bunet</b> and his Personal Skill, "<b>Seconds?</b>". <b>When Bunet eats a Packed Lunch, he has a Luck% chance of obtaining another Packed Lunch</b>. To get the most out of this, it's a good idea for Bunet to inherit a Luck+ Skill to stack with Byleth's passive Luck Boost to increase the chances of his Personal Skill triggering. <br><br>

The problem with this build is that for story reasons, when Bunet joins, Celica is unavailable along with her Skill Inheritance. So build will take time to properly assemble. <br><br> 

This is a gimmicky joke build you could run for fun if you want to spam back-to-back Goddess Dances without having to manually refill Byleth's Engage Meter. If you're into memes, then I recommend trying this build at least once.  

</details>


# **Final Thoughts** <br>
As the last of the 12 Emblems, Byleth does not disappoint. He can fill the roles of both Support and Combat but which side he leans toward depends on who's wearing his ring. His Engage Attack is arguably the best in the game, especially if you know how to push it to its limits. Even Units who aren't wearing his ring benefit from his good and dirt-cheap Skill Inheritance. <br>

As stated before, Byleth is as simple or complex as you want him to be. Whether you want to run him as a dedicated Support Refresher or another Combat-focused Emblem, Byleth has you covered. <br>

One has to wonder though. Was Byleth holding back his true power back in Three Houses by not speaking? Maybe if Byleth could speak, that would have irreparably altered Fodlan's history for ever. We may never know. 




