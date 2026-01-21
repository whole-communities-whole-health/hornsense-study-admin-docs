# Item checkout and return
The database records item history for all properly checked out/checked in study materials with barcodes.

If an item is currently checked in, and inactive, here are the steps to check the item out to another participant and then to check that item in again when the participant is finished with it. You can think of this as one complete "cycle" of item use:

1. Make item active, assign checkout timestamp, and check out to participant. These actions are in the same admin panel screen.  
2. Mark item as scanned by participant, or participant scans item (item then shows in admin panel history and in database).  
3. Check item in when participant is done with it.  
4. Mark item as returned. The item is now inactive again and ready to be checked out to the next participant. The admin panel shows a confirmation message at this stage, "Study material xxxxxxx was checked in at 07/29/2024 at 4:56 PM. Assign the material to a new participant or just click 'Save'."  