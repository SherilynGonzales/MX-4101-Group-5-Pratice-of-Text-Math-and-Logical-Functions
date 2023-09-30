# MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions
𝑨𝒖𝒕𝒉𝒐𝒓/𝒔: 𝘑𝘰𝘩𝘯 𝘙𝘦𝘺 𝘋𝘦𝘤𝘢𝘯𝘰, 𝘚𝘩𝘦𝘳𝘪𝘭𝘺𝘯 𝘎𝘰𝘯𝘻𝘢𝘭𝘦𝘴, 𝘢𝘯𝘥 𝘍𝘳𝘪𝘵𝘻 𝘎𝘢𝘣𝘳𝘪𝘦𝘭 𝘗𝘢𝘭𝘮𝘢

Basic Text, Math, and Logical Functions are highlighted in this section along with information on how to utilize and manipulate them in Microsoft Excel. Every definition of a function includes a reference to its syntax.

𝐀. 𝐓𝐄𝐗𝐓 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬

Excel is mostly about numerical data, but at times you can come across data that has too much text and that's the time when Text Functions in Excel will help you to simplify things easily.

Usage Scenarios:

1. Conversion from lowercase to uppercase.
2. Used to find the substring within a string.
3. Used to extract a substring from a string.
4. List specific words or characters from a string.


  A.1. LEN

  The Microsoft Excel TRIM function returns the length of the specified string.  

  𝑺𝒚𝒏𝒕𝒂𝒙

  = 𝘓𝘌𝘕( 𝘵𝘦𝘹𝘵)

  A.2. TRIM
  
  The Microsoft Excel TRIM function returns a text value with the leading and trailing spaces removed. You can also use the TRIM function to remove unnecessary spaces between words in a string.

  𝑺𝒚𝒏𝒕𝒂𝒙

  = 𝘛𝘙𝘐𝘔( 𝘵𝘦𝘹𝘵)
  
  A.3. UPPER

  The Microsoft Excel UPPER function allows you to convert text to all uppercase.

  𝑺𝒚𝒏𝒕𝒂𝒙

  =𝘜𝘗𝘗𝘌𝘙(𝘵𝘦𝘹𝘵)
  
  A.4. LOWER

  The Microsoft Excel UPPER function allows you to convert text to all lowercase.

  𝑺𝒚𝒏𝒕𝒂𝒙

  =𝘓𝘖𝘞𝘌𝘙(𝘵𝘦𝘹𝘵)
  
  A.5. PROPER

  The Microsoft Excel PROPER function sets the first character in each word to uppercase and the rest to lowercase.

   𝑺𝒚𝒏𝒕𝒂𝒙

   = 𝘗𝘙𝘖𝘗𝘌𝘙(𝘵𝘦𝘹𝘵)
   
  A.6. SUBSTITUTE

  The Microsoft Excel SUBSTITUTE function replaces a set of characters with another.

   𝑺𝒚𝒏𝒕𝒂𝒙

   =𝘚𝘜𝘉𝘚𝘛𝘐𝘛𝘜𝘛𝘌(𝘵𝘦𝘹𝘵,𝘰𝘭𝘥_𝘵𝘦𝘹𝘵,𝘯𝘦𝘸_𝘵𝘦𝘹𝘵, [𝘯𝘵𝘩_𝘢𝘱𝘱𝘦𝘢𝘳𝘢𝘯𝘤𝘦])
   
  Parameters
  
  -> text - The original string to use to perform the substitution
  
  -> old_text - The existing characters to replace
 
  -> new_text - The new characters to replace old_text with. 
 
  -> nth_appearance Optional It is the nth appearance of the old_text that you wish to replace. If this parameter is omitted, then every occurrence of old_text will be replaced with test text

  A.7. REPLACE

  The Microsoft Excel REPLACE function replaces a sequence of characters in a string with another set of characters.

   𝑺𝒚𝒏𝒕𝒂𝒙
   
   =𝘙𝘌𝘗𝘓𝘈𝘊𝘌( 𝘰𝘭𝘥_𝘵𝘦𝘹𝘵, 𝘴𝘵𝘢𝘳𝘵, 𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘴, 𝘯𝘦𝘸_𝘵𝘦𝘹𝘵 )
   
  Parameters
  
  -> old_ text - The original string value.
  
  -> start - The position in old_text to begin replacing characters.
  
  -> number_of_chars - The number of characters to replace in old text
  
  -> new_text - The replacement set of characters


  A.8. FIND

  The Microsoft Excel FIND function returns the location of a substring in a string. The search is case-sensitive

   𝑺𝒚𝒏𝒕𝒂𝒙

   =𝘍𝘐𝘕𝘋(𝘴𝘶𝘣𝘴𝘵𝘳𝘪𝘯𝘨,𝘴𝘵𝘳𝘪𝘯𝘨,[𝘴𝘵𝘢𝘳𝘵_𝘱𝘰𝘴𝘪𝘵𝘪𝘰𝘯))
   
  Parameters
  
 ->  substring - The substring that you want to find
  
  -> string - The string to search within.
  
  -> start_position - Optional. It is the position in string where the search will start. The first position is 1. If the start_position is not provided, the FIND function will start the search at the beginning of the string
  
  A.9. LEFT

  The Microsoft Excel LEFT function allows you to extract a substring from a string, starting from the leftmost character.

   𝑺𝒚𝒏𝒕𝒂𝒙

   =𝘓𝘌𝘍𝘛(𝘵𝘦𝘹𝘵,[𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘢𝘤𝘵𝘦𝘳𝘴])

  Parameters
 
  -> text - The string that you wish to extract from.
  
  -> number_of_characters - Optional. It indicates the number of characters that you wish to extract starting from the leftmost character, If this parameter is omitted, only 1 character is returned.

  A.10. RIGHT

  The Microsoft Excel RIGHT returns the last character or characters in a text string, based on the number of characters you specify.

   𝑺𝒚𝒏𝒕𝒂𝒙


  =𝘙𝘐𝘎𝘏𝘛(𝘵𝘦𝘹𝘵,[𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘢𝘤𝘵𝘦𝘳𝘴])
  
  Parameters
  
  -> text - The string that you wish to extract from.
  
  -> number_of_characters - Optional. It indicates the number of characters that you wish to extract starting from the leftmost character. If this parameter is omitted, only 1 character is returned

  A.11. MID

  The Microsoft Excel MID function extracts a substring from a string (starting at any position).

   𝑺𝒚𝒏𝒕𝒂𝒙

   =𝘔𝘐𝘋(𝘵𝘦𝘹𝘵,𝘴𝘵𝘢𝘳𝘵_𝘱𝘰𝘴𝘪𝘵𝘪𝘰𝘯,𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘢𝘤𝘵𝘦𝘳𝘴)
   
   Parameters
  
  -> text - The string that you wish to extract from.
  
  -> start_position - The position in the string that you will begin extracting from. The first position in the string is 1. 
  
  -> number_of_characters - The number of characters that you wish to extract. It is mandatory when the MID function is used as a Worksheet function, but optional in VBA. (if you omit this parameter in VBA, the MID function will return all characters after the start_position.)

  A.12. CONCATENATE

The Microsoft Excel CONCATENATE function allows you to join 2 or more strings together. 

   𝑺𝒚𝒏𝒕𝒂𝒙

   =𝘊𝘖𝘕𝘊𝘈𝘛𝘌𝘕𝘈𝘛𝘌(𝘵𝘦𝘹𝘵1, [𝘵𝘦𝘹𝘵2, … 𝘵𝘦𝘹𝘵_𝘯])
   
𝐁. 𝐌𝐀𝐓𝐇 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬

𝐂. 𝐋𝐨𝐠𝐢𝐜𝐚𝐥 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬
