<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<title>Low Magic World</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link rel="stylesheet" href="style/g3readme_cam.css" type="text/css" />
<link href="style/g3icon.ico" rel="icon" type="image/bmp" />
</head>
<body>
<h1>Low Magic World</h1>
<div class="section">
  <p><strong>Author: <a href="http://forums.gibberlings3.net/index.php?showuser=6306">various peeps</a><br />
    On the web: <a href="https://github.com/UnearthedArcana/Low_Magic">Home page</a></strong> and <strong><a href="https://forums.beamdog.com/categories/general-modding">discussion forums</a></strong></p>
  <p><strong> Version 0.3 </strong><br />
    <strong> Languages:</strong> English<br />
</div>
<h2>Overview</h2>
<div class="section">
    <p><b><i>Component #100: No Generic Magic Items</i></b></p>
    <p>This component aims to reduce the amount and influence of magic items that are barfed all over the world.</p>
    <p>Part of this is just for show: it removes the fourth-wall-breaking "+1," "+2," etc. from item names.  Also, it de-enchants almost all "generic" magical equipment and standardizes the enchantment levels of weapons for purposes of which enemies they can hit:</p>
    <ul>
      <li> ALL generic +1, +2, and +3 items become "Mastercraft" items, forged with unusual materials and skill but not actually enchanted.</li>
      <li> All named weapons that were formerly from +1 to +4, become +3 weapons for purposes of what they can hit - though their bonuses and magical abilities remain unchanged.</li>
      <li> All upgraded weapons and originally +5/+6 weapons become +5 for purposes of what they can hit.</li>
    </ul>
    <p>(This component does not work on IWDEE - too many items are defined and recognized by the "plus" in their names and descriptions.</p>
    <p><b>Compatibility:</b> this component covers the same ground as the SCS component "Make +1 Weapons Into Fine Weapons." This component also has other effects, of course. You should not install that component of SCS if you want to use this component.</p>
</div>
<div class="section">
    <p><b><i>Component #200: No Spell Level Scaling</i></b></p>
    <p>This component limits the power of spellcasting, by removing level scaling is from all spells.  So Fireballs will only ever do 5d6 damage, DUHM will only ever add 1 point to your stats, etc.</p>
</div>
<div class="section">
    <p><b><i>Component #300: Reduced Spell Durations</i></b></p>
    <p>This component further limits the power of spellcasting by reducing and standardizing all spell durations, to 3 rounds, 6 rounds, 2 turns, or 4 hours, depending on the duration of the original spell.</p>
</div>
<div class="section">
    <p><b><i>Component #400: Increased Price of Magic Scrolls</i></b></p>
    <p>This component increases the price of scrolls.  Arcane scrolls that allow you to learn spells can either be 100 times the square of the spell level (so, 8,100gp for 9th level spells), or simply triple the vanilla scroll price.  Other scrolls will be triple the normal price.</p>
</div>
<div class="section">
    <p><b><i>Component #500: Weaponized Wands</i></b></p>
    <p>This component changes most of the wands in the game into magical weapons for use by arcane spellcasters. Wands always hit, do not benefit from weapon proficiencies, cannot critically hit, set attacks per round to one and have a range of 30 feet. 
    <ul>
      <li> Wand of Missiles: 2d3 magic damage </li>
      <li> Wand of Fire: 2d4 fire damage (save vs. wand -2 for half damage); choice of two different area of effect patterns (30' ray, 3' burst) </li>
      <li> Wand of Frost: 1d4 cold damage; slows for 2 rounds (save vs. wand -2 negates slow) </li>
      <li> Wand of Lightning: 1d6 electric damage; can pierce through creatures and bounce off walls </li> 
      <li> Wand of the Heavens: 1d4 fire damage; +1d4 magic damage against evil (druids and priests only) </li> 
      <li> Wand of Cloudkill: 1d6 poison damage; slays creatures with 6 or fewer HD (save vs. wands -2 negates slay) </li> 
      <li> Wand of Corrosion: 1d4 acid damage; -2 penalty to Armor Class for 1 round (IWD only) </li> 
      <li> Wand of Many Missiles: 5d3 magic damage (IWD only) </li> 
      <li> Wand of Fear: panic for 2 rounds (save vs. wands -2 negates) </li> 
      <li> Wand of Paralyzation: stun for 1 round (save vs. wands -2 negates) </li> 
      <li> Wand of Sleep: sleep for 2 rounds or until damaged (save vs. wands -2 negates) </li> 
      <li> Wand of Polymorph: polymorph into a squirrel 1 round (save vs. wands -2 negates) </li> 
      <li> Wand of Cursing: choice of either blind for 2 rounds or silence for 2 rounds (save vs. wands -2 negates either) </li> 
      <li> Wand of Spellstriking: choice of either remove combat protections (4th level or lower) or remove spell protections (4th level or lower) (save vs. wands -2 negates either) </li> 
      <li> Wand of Summoning: summon an ogre, hogoblin, dire wolf, or gnoll adjacent to target for 2 rounds (IWD only) </li> 
    </ul>
    </p>
</div>
<div class="section">
    <p><b><i>Component #600: Slower XP Advancement for Fighters and Rogues</i></b></p>
    <p>Since this mod can pretty severely weaken spellcasters, relative to warriors, it makes sense that warriors should advance in poer more slowly.  This component puts fighters onto the paladin/ranger XP table, and puts thieves and bards onto the old fighter XP table.</p>
</div>
</body>
</html>
