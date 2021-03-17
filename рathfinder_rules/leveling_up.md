# Leveling up

## Leveling-Up Checklist

1. Increase your level by 1.
1. Increase your maximum Hit Points by the amount listed in your [class entry](https://2e.aonprd.com/Classes.aspx).
1. Add **class features** from your [class](https://2e.aonprd.com/Classes.aspx) advancement table.
1. Select feats as indicated on your [class](https://2e.aonprd.com/Classes.aspx) advancement table. For ancestry feats, see [Ancestries](https://2e.aonprd.com/Ancestries.aspx). For class feats, see your [class entry](https://2e.aonprd.com/Classes.aspx). For general feats and skill feats, see [Feats](https://2e.aonprd.com/Feats.aspx) (*skill feats* type of *general feats*, so you can select *skill feat* in place of *general feat*).
1. Add spells and spell slots if your class grants spellcasting. See [Spells](https://2e.aonprd.com/Spells.aspx) for spells. If your class has *signature spells* feature select them. (Note that your cantrips and focus spells heightened to maximum level available to you)
1. Gain ability boosts as staited in [Gradual Ability Boosts](https://2e.aonprd.com/Rules.aspx?ID=1300).
1. Add new bonus from [Automatic Bonus Progression](https://2e.aonprd.com/Rules.aspx?ID=1357) table.
1. Adjust bonuses from feats and other abilities that are based on your level or you proficiencies.

### Leveling-Up using **character.pf2.tools**

1. Increase your level by 1.  
   !![](screen/level-1.png)
   !![](screen/level-2.png)
1. Hit Points increase done automatically.
1. Add **class features** from your [class](https://2e.aonprd.com/Classes.aspx) advancement table.
   Proficiencies can be changed for everething if corresponding menu. (Note that spellcasting and skill have different proficiency. Occultism and occult spellcasting for example.)      
   !![](screen/prof.png)  
   Features can be added using :fontawesome-solid-search-plus:  
   !![](screen/feature.png)  
1. Select feats as indicated on your [class](https://2e.aonprd.com/Classes.aspx) advancement table. For ancestry feats, see [Ancestries](https://2e.aonprd.com/Ancestries.aspx). For class feats, see your [class entry](https://2e.aonprd.com/Classes.aspx). For general feats and skill feats, see [Feats](https://2e.aonprd.com/Feats.aspx) (skill feats type of general feats, so you can select skill feat in place of general feat).  
   Feats can be added automatically using :fontawesome-solid-search-plus:  
   !![](screen/feats.png)  
1. Add spells and spell slots if your class grants spellcasting. See [Spells](https://2e.aonprd.com/Spells.aspx) for spells. If your class has *signature spells* feature select them. (Note that your cantrips and focus spells heightened to maximum level available to you)  
   Spell slots added here:  
   !![](screen/spell-1.png)
   !![](screen/spell-2.png)  
   Spells can be added here using :fontawesome-solid-search-plus:    
   !![](screen/spell-3.png)  
   Focus spells:  
   !![](screen/spell-4.png)  
1. Gain ability boosts as staited in [Gradual Ability Boosts](https://2e.aonprd.com/Rules.aspx?ID=1300).  
   !![](screen/abl-1.png)   
   !![](screen/abl-2.png)   
1. Add new bonus from [Automatic Bonus Progression](https://2e.aonprd.com/Rules.aspx?ID=1357) table.  
   Change `ADJUSTMENT`: `AUTOMATIC BONUS PROGRESSION`. Replace `SKILLNAME` with skill if required (`PERFORMANCE` for example)
        ``` 
            ATTACK +X ITEM
            SKILLNAME +X ITEM
            DAMAGEDICE +X ITEM
            AC +X ITEM
            PERCEPTION +X ITEM
            SAVES +X ITEM
        ```
   !![](screen/adj-1.png)   
   !![](screen/adj-2.png)   
1. Adjust bonuses from feats and other abilities that are based on your level or you proficiencies. (New formulas, extra damage, new familiar abilities...)