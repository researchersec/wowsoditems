- ItemSparse.csv - ID(int) + Display_lang(text) + OverallQualityID(int)
  - OverallQualityID can be 0-5
  - 0 = Poor
  - 1 = Common
  - 2 = Uncommon
  - 3 = Rare
  - 4 = Epic
  - 5 = Legendary
 
    
- Item.csv - ID(int) + IconFileDataID(int)
- Icons.csv - IconFileDataID(int) ~ ID(int) + ModifiedPath(text)


**ItemSparse.csv:**

```csv
ID,AllowableRace,Description_lang,Display3_lang,Display2_lang,Display1_lang,Display_lang,DmgVariance,DurationInInventory,QualityModifier,BagFamily,StartQuestID,ItemRange,StatPercentageOfSocket_0,StatPercentageOfSocket_1,StatPercentageOfSocket_2,StatPercentageOfSocket_3,StatPercentageOfSocket_4,StatPercentageOfSocket_5,StatPercentageOfSocket_6,StatPercentageOfSocket_7,StatPercentageOfSocket_8,StatPercentageOfSocket_9,StatPercentEditor_0,StatPercentEditor_1,StatPercentEditor_2,StatPercentEditor_3,StatPercentEditor_4,StatPercentEditor_5,StatPercentEditor_6,StatPercentEditor_7,StatPercentEditor_8,StatPercentEditor_9,Field_1_15_3_55112_014_0,Field_1_15_3_55112_014_1,Field_1_15_3_55112_014_2,Field_1_15_3_55112_014_3,Field_1_15_3_55112_014_4,Field_1_15_3_55112_014_5,Field_1_15_3_55112_014_6,Field_1_15_3_55112_014_7,Field_1_15_3_55112_014_8,Field_1_15_3_55112_014_9,Stackable,MaxCount,MinReputation,RequiredAbility,SellPrice,BuyPrice,VendorStackCount,PriceVariance,PriceRandomValue,Flags_0,Flags_1,Flags_2,Flags_3,OppositeFactionItemID,ModifiedCraftingReagentItemID,ContentTuningID,PlayerLevelToItemLevelCurveID,MaxDurability,ItemNameDescriptionID,RequiredTransmogHoliday,RequiredHoliday,LimitCategory,Gem_properties,Socket_match_enchantment_ID,TotemCategoryID,InstanceBound,ZoneBound_0,ZoneBound_1,ItemSet,LockID,PageID,ItemDelay,MinFactionID,RequiredSkillRank,RequiredSkill,ItemLevel,AllowableClass,ItemRandomSuffixGroupID,RandomSelect,MinDamage_0,MinDamage_1,MinDamage_2,MinDamage_3,MinDamage_4,MaxDamage_0,MaxDamage_1,MaxDamage_2,MaxDamage_3,MaxDamage_4,Resistances_0,Resistances_1,Resistances_2,Resistances_3,Resistances_4,Resistances_5,Resistances_6,ScalingStatDistributionID,StatModifier_bonusAmount_0,StatModifier_bonusAmount_1,StatModifier_bonusAmount_2,StatModifier_bonusAmount_3,StatModifier_bonusAmount_4,StatModifier_bonusAmount_5,StatModifier_bonusAmount_6,StatModifier_bonusAmount_7,StatModifier_bonusAmount_8,StatModifier_bonusAmount_9,ExpansionID,ArtifactID,SpellWeight,SpellWeightCategory,SocketType_0,SocketType_1,SocketType_2,SheatheType,Material,PageMaterialID,LanguageID,Bonding,DamageType,StatModifier_bonusStat_0,StatModifier_bonusStat_1,StatModifier_bonusStat_2,StatModifier_bonusStat_3,StatModifier_bonusStat_4,StatModifier_bonusStat_5,StatModifier_bonusStat_6,StatModifier_bonusStat_7,StatModifier_bonusStat_8,StatModifier_bonusStat_9,ContainerSlots,RequiredPVPMedal,RequiredPVPRank,InventoryType,OverallQualityID,AmmunitionType,RequiredLevel
25,-1,,,,,"Worn Shortsword",0.60000002384,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0,7,35,1,1,1,0,24580,0,0,0,0,0,0,20,0,0,0,0,0,0,0,0,0,0,0,0,0,1900,0,0,0,2,-1,0,0,1,0,0,0,0,3,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,254,0,0,0,0,0,0,3,1,0,1,0,0,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,0,0,0,21,1,0,1
35,-1,,,,,"Bent Staff",0.40000000596,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0,9,47,1,1,1,0,24580,0,0,0,0,0,0,25,0,0,0,0,0,0,0,0,0,0,0,0,0,2900,0,0,0,2,-1,0,0,3,0,0,0,0,5,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,254,0,0,0,0,0,0,2,2,0,0,0,0,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,0,0,0,17,1,0,1
```

**Item.csv:**

```csv
ID,ClassID,SubclassID,Material,InventoryType,RequiredLevel,SheatheType,RandomSelect,ItemRandomSuffixGroupID,Sound_override_subclassID,ScalingStatDistributionID,IconFileDataID,ItemGroupSoundsID,ContentTuningID,MaxDurability,AmmunitionType,ScalingStatValue,DamageType_0,DamageType_1,DamageType_2,DamageType_3,DamageType_4,Resistances_0,Resistances_1,Resistances_2,Resistances_3,Resistances_4,Resistances_5,Resistances_6,MinDamage_0,MinDamage_1,MinDamage_2,MinDamage_3,MinDamage_4,MaxDamage_0,MaxDamage_1,MaxDamage_2,MaxDamage_3,MaxDamage_4
17,4,4,6,4,0,3,0,0,-1,0,132759,11,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0
25,2,7,1,21,1,3,0,0,-1,0,135274,8,0,20,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0,0,3,0,0,0,0
```

**Icons.csv:**

```csv
ID,ModifiedPath
132089,ability_ambush
132090,ability_backstab
```
