# catcount
My improvements on the Category Count module by Zac Gordon - Wide Sky Web Company
Description:

Returns the number of entries for a given category.

------------------------------------------------------
		
Example:


{exp:catcount cat_id="33" status="open|closed"}

Returns
3

------------------------------------------------------

Parameters:

channel=“posts|events”
Filters the results for only the channels you provide. Optional.

cat_id="1"
The id for the category that you want to output the number of entries for.

status="open|closed"
Determines the status of entries you want to count.  Default setting is "open"

expired="yes"
Will include entries that have expired. 