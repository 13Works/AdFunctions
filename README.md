# All Ad functions
**Every ingame remote is avalible as a function, this list is for known arguments**
**If this list is inaccurate or if you want me to add more customs then dm me on discord "13works"**

## From AdoptAPI
**Ad.EjectAllHeldBabies(Object)**;
> 'Object' is an object representing the entity from which babies should be ejected

**Ad.HoldBaby(Object)**;
> 'Object' is an object representing a baby

**Ad.FlyPet(Object)**;
> 'Object' is a pet object

**Ad.RidePet(Object)**;
> 'Object' is a pet object

***

## From DailyLoginAPI
**Ad.ClaimDailyReward()**;

**Ad.ClaimStarReward(RewardName)**;
> 'RewardName' is a string representing the name of the reward being claimed

***

## From FamilyAPI
**Ad.AcceptDeclineInvite(Choice)**;
> 'Choice' is a boolean representing whether to accept (true) or decline (false) a family invitation

**Ad.ChangeFamilyName(Name)**;
> 'Name' is a string representing the new family name

**Ad.CreateFamily()**;

**Ad.GetFamilyMemberLocations()**;

**Ad.InvitePlayer(Player)**;
> 'Player' is a Player object representing the player to invite to the family

**Ad.LeaveFamily()**;

***

## From HousingAPI

**Ad.ActivateFurniture(Player, FurnitureName, Action, Positioning, Target)**;

>* 'Player' is a Player object.
>* 'FurnitureName' is a string representing the name of the furniture.
>* 'Action' is a string with possible values "UseBlock" or "Seat1".
>* 'Positioning' is a table with a 'cframe' key representing the position.
>* 'Target' is a string or a Player object.

**Ad.BuyFurnitures(Furniture)**;
> 'Furniture' is a table containing furniture data.

**Ad.BuyHouseWithAddons(HouseName, Unknown, Color)**;
>* 'HouseName' is a string representing the name of the house.
>* 'Unknown' is an unknown data type.
>* 'Color' is a Color3 object.

**Ad.UnsubscribeFromHouse(Player, Choice)**;
>* 'Player' is a Player object.
>* 'Choice' is a boolean representing whether to unsubscribe (true) or not (false).

**Ad.GetWholeHouseValue(HouseIndex)**;
> 'HouseIndex' is a number representing the index of the house.

**Ad.PushFurnitureChanges()**;

**Ad.RenameHouse(HouseIndex, HouseName)**;
>* 'HouseIndex' is a number representing the index of the house.
>* 'HouseName' is a string representing the new house name.

**Ad.RateParty(TargetPlayer, Rating)**;
>* 'TargetPlayer' is a Player object.
>* 'Rating' is a string with possible values "great," "good," or "bad."

**Ad.SellFurniture(FurnitureNames)**;
> 'FurnitureNames' is a table of strings representing the names of furniture items to sell.

**Ad.SellHouse(HouseIndex)**;
> 'HouseIndex' is a number representing the index of the house to sell.

**Ad.SetDoorLocked(Choice)**;
> 'Choice' is a boolean representing whether to set the door locked (true) or unlocked (false).

**Ad.SpawnHouse(HouseIndex)**;
> 'HouseIndex' is a number representing the index of the house to spawn.

**Ad.ThrowParty(Properties)**;
> 'Properties' is a table containing properties of the party.

***

## From LocationAPI
**Ad.GetCharacterRootCframe(Player)**;
> 'Player' is a Player object.

**Ad.SetLocation(LocationType, DoorType, Owner)**;
>* 'LocationType' is a string representing the location type.
>* 'DoorType' is a string with possible values "Default" or "MainDoor."
>* 'Owner' is an optional Player object.

**Ad.TeleToPlayer(Player)**;
> 'Player' is a Player object.

***

## From MonitorAPI
**Ad.AddAdditive(AilmentName, Rate)**;
> 'AilmentName' is an Ailment (unspecified type).
> 'Rate' is a number.

**Ad.HealWithDoctor()**;

***

## From PetAPI
**Ad.DoNeonFusion(Uniques)**;
> 'Uniques' is a table of 4 strings.

***

## From PetObjectAPI
**Ad.CreatePetObject(EnumType, Properties)**;
> 'EnumType' is a string representing the type of the pet object.
> 'Properties' is a table containing properties of the pet object.

**Ad.ConsumeFoodItem(Unique)**;
> 'Unique' is a string representing the unique identifier of a food item.

***

## From QuestAPI
**Ad.ClaimQuest(QuestId)**;
> 'QuestId' is a string representing the ID of the quest to claim.

**Ad.MarkQuestsViewed()**;

***

## From SettingsAPI
**Ad.SetPetRoleplayName(PetName)**;
> 'PetName' is a string representing the roleplay name of a pet.

**Ad.SetSetting(SettingName, Value)**;
> 'SettingName' is a string representing the name of the setting.
> 'Value' can be of any type, representing the value to set for the setting.

***

## From ShopAPI
**Ad.BuyItem(Category, Kind)**;
> 'Category' is a string with possible values "pets," "food," "transport," "gifts," or "strollers."
> 'Kind' is a string representing the kind of item to buy.

**Ad.OpenGift(Unique)**;
> 'Unique' is a string representing the unique identifier of a gift item.

***

## From TeamAPI
**Ad.ChooseTeam(Team, Choice)**;
> 'Team' is a string with possible values "Babies" or "Parents."
> 'Choice' is a boolean representing the choice to make (true/false).

***

## From ToolAPI
**Ad.Equip(Unique)**;
> 'Unique' is a string representing the unique identifier of a tool to equip.

**Ad.Unequip(Unique)**;
> 'Unique' is a string representing the unique identifier of a tool to unequip.

**Ad.UnequipAll()**;

***
## From TradeAPI

**Ad.AcceptNegotiation()**;

**Ad.AcceptOrDeclineTradeRequest(Choice)**;
> 'Choice' is a boolean representing whether to accept (true) or decline (false) a trade request.

**Ad.AddItemToOffer(Unique)**;
> 'Unique' is a string representing the unique identifier of an item to add to the trade offer.

**Ad.AnswerQuizQuestion(Answer)**;
> 'Answer' is unspecified.

**Ad.BeginQuiz()**;

**Ad.ConfirmTrade()**;

**Ad.DeclineTrade()**;

**Ad.DeclineNegotiation()**;

**Ad.EndQuiz()**;

**Ad.GiveItem(Player, Unique)**;
> 'Player' is a Player object representing the player to give the item to.
> 'Unique' is a string representing the unique identifier of an item to give.

**Ad.RemoveItemFromOffer(Unique)**;
> 'Unique' is a string representing the unique identifier of an item to remove from the trade offer.

**Ad.SendTradeRequest(Player)**;
> 'Player' is a Player object representing the player to send the trade request to.

**Ad.UnacceptNegotiation()**;

***

## From TutorialAPI
**Ad.MarkTutorialCompleted()**;

**Ad.CompleteExploreNursery()**;

**Ad.GiveTutorialReward()**;

***

## Customs

**Ad:GetInventory()**;
> Returns inventory data.

**Ad:GetAilments()**;
> Returns an array of strings representing ailment names.

**Ad:GetFullgrownPets()**;
> Returns all full-grown pets in the player's inventory.

**Ad:GetLuminousPets()**;
> Returns all luminous pets in the player's inventory.

**Ad:GetQuestIds()**;
> Returns an array of quest Ids.

**Ad:GetFurniture()**;
> Returns an array of all furniture in the player's current location.

**Ad:FindFurniturePiece(TargetPiece)**;
> 'TargetPiece' is a string representing the name of the furniture to find.

**Ad:GetHouseOrigin()**;
> Returns the origin position of the player's current house.

**Ad.Spawn()**;
> Spawns the player in the game if player is in menu.
