# phoneregex
Regex pattern for armenian phone numbers

	Current version ^([+374]{4}|[0]{1})?([1-9]{2})(((-\d{3}-\d{3})|(-\d{2}-\d{2}-\d{2})|( \d{3} \d{3})|( \d{2} \d{2} \d{2}))|(\d{6}))$	
	
		Accepted + with letter number(374 possibly) OR 0 then sequence of digits with allowed range
		
		Spaces, dashes are allowed only in right sequence (dash followed by dash, space followed by space - separated with two-digit number օr tհree-digit number)
		
		Other symbols are not allowed
		
		Currenty thinking to developer version with dashes/spaces for example : +374-99-222-84 OR +374 99 22 26 84
		
		Live demo [Regex101](https://regex101.com/r/d4DW2m/1)

		Contributions are welcome
