## A matrix generated by shifting the zeroth row  
Originally published: 2012-06-03 17:46:18  
Last updated: 2012-06-05 12:38:36  
Author: Andrej T.  
  
ShiftMatrix is a class that generates matrix values by shifting the zeroth row left or right length_of_row times. For example: if you initialize it with sm = ShiftMatrix([1,2,3]), sm[1] will return [3,1,2]. Only the initial list is stored, the other values are generated at runtime.