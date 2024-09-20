# Item checkout and return
The database records item history for all properly checked out/checked in items. If an item is currently checked in, and inactive, here is the correct way to check the item out to a participant and then to check that item in when the participant is finished with it (one complete "cycle" of item use):

1. Make item active, assign checkout timestamp, and check out to participant (All actions in the same admin panel screen).  
2. Mark item as scanned by participant, or participant scans item (item then shows in admin panel history and in database).  
3. Check item in when participant done with it.  
4. Mark item as returned (item now inactive again and ready to be checked out to new participant). The admin panel shows a confirmation message at this stage, "Study material xxxxxxx was checked in at 07/29/2024 at 4:56 PM. Assign the material to a new participant or just click 'Save'."  