#  Week 3 Assessment – Regular Expressions

##  Section 1: Multiple Choice Questions 

1. **What does 're' stand for in Python?** 

   A. Regular Expression ✔️

   B. Random Execution

   C. Regex Engine

   D. Recursive Evaluation


2. **Which function finds all matches of a pattern in a string?** 

   A. match()

   B. search()

   C. findall() ✔️

   D. compile()


3. **What symbol matches any single character except a newline?** 

   A. *

   B. . ✔️

   C. +

   D. ^


4. **Which character is used to match the start of a string?** 

   A. ^ ✔️

   B. $

   C. ?

   D. .


5. **Which regex symbol matches zero or more occurrences?** 

   A. +

   B. * ✔️

   C. ?

   D. .


6. **What will re.findall(r'\d+', 'abc123xyz45') return?** 

   A. ['abc', 'xyz']

   B. ['123', '45'] ✔️

   C. ['1', '2', '3', '4', '5']

   D. []


7. **Which function returns a match object if pattern is found at the start?** 

   A. search()

   B. match() ✔️

   C. findall()

   D. fullmatch()


8. **What is the output of re.search(r'abc', '123abc456')?** 

   A. None

   B. Match object ✔️

   C. ['abc'] 

   D. Error


9. **What does re.sub(r'\d', '*', 'a1b2c3') return?** 

   A. 'abc'

   B. 'a*b*c*' ✔️

   C. 'a1b2c3'

   D. '*a*b*c*'


10. **What does re.split(r'\s+', 'a b   c') return?** 

     A. ['a', 'b', 'c'] ✔️

    B. ['a b   c']

     C. ['a', '', '', 'b', '', '', '', 'c']

    D. Error


11. **Which pattern matches a 10-digit phone number like 9876543210?**

     A. r'\d{10}' ✔️

    B. r'\d(10)'

     C. r'\d\d\d\d\d\d\d\d\d\d'

     D. r'\D{10}'


12. **Which pattern matches a word boundary?** 

     A. r'^'

     B. r'$'

     C. r'\b' ✔️

     D. r'\w'


13. **What is the output of re.findall(r'[^0-9]', 'a1b2c3')?** 

    A. ['1', '2', '3']

     B. ['a', 'b', 'c'] ✔️

     C. []

     D. Error


14. **Which of these patterns matches an empty string?** 

    A. r'^$' ✔️
    
     B. r'\s' 
    
     C. r'\w'
    
    D. r'.*'
    

15. **Which of these is a valid use of raw string in regex?** 

     A. re.compile('\n')
    
     B. re.compile(r'\n') ✔️
    
     C. re.compile('\\n')
    
     D. All of the above
    

16. **What is the output of re.findall(r'\b\w{4}\b', 'This is a test of code regex')?**

     A. ['This', 'test', 'code'] ✔️
     
     B. ['test']
    
    C. ['This', 'test', 'code', 'regex']
    
     D. []
    

17. **What does re.match(r'.*', '') return?** 

    A. None
   
    B. Match object ✔️
   
    C. ''
   
     D. Error
   

18. **What is the output of re.sub(r'(\d+)', r'\1\1', 'abc123def')?** 

    A. 'abc123123def' ✔️
   
     B. 'abc\1\1def' 
   
     C. 'abc12def'
   
     D. 'abc1def'
   

19. **Which regex pattern matches 'cat' or 'cot' but not 'cut'?** 

    A. r'c[ao]t' ✔️
   
    B. r'c[cat|cot]'
   
    C. r'c[^u]t'
   
    D. r'c[a|o]t' 
   

20. **What is the difference between re.search() and re.match()?** 

    A. No difference
   
    B. search() looks anywhere, match() only at the start ✔️
   
     C. match() looks anywhere, search() only at start
   
    D. match() returns a list
   

