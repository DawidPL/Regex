# Regex
### PhoneNumberRegex

This regular expression is dedicated to Polish numbers which can be found on websites. Contains (probably) all combinations.  
Remember that all expression are case sensitive!. In order to searching through uppercase and lowercase letters you need to add
"i" between words in expression. For example in this case(Python):

#### (telefoniczny|telefon|tel|fax|kom) 
change to:
#### (?i)(telefoniczny|telefon|tel|fax|kom)(?-i)

___
(?i) - starts case-insensitive mode

(?-i) - turns off case-insensitive mode
___
