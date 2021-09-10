# Word-finder-and-replacer
n this tutorial, we will learn about the Python replace() method with the help of examples.

The replace() method replaces each matching occurrence of the old character/text in the string with the new character/text.
                            
                            text = 'bat ball'

                          # replace b with c
                            replaced_text = text.replace('b', 'c')
                            print(replaced_text)

                          # Output: cat call
# replace() Syntax
It's syntax is:

                           str.replace(old, new [, count])    
# replace() Parameters
The replace() method can take maximum of 3 parameters:

 (*) old - old substring you want to replace
 (*) new - new substring which will replace the old substring
 (*) count (optional) - the number of times you want to replace the old substring with the new substring                          

                        Note: If count is not specified, the replace() method replaces all occurrences of the old substring with the new substring.
              
# replace() Return Value
The replace() method returns a copy of the string where the old substring is replaced with the new substring. The original string is unchanged.

If the old substring is not found, it returns the copy of the original string. 
