 boolean check(s: string):
   counter = 0
   for i = 1 to length(s)
     if s[i] == '('
       counter++
     else
       counter-- 
     if counter < 0
       return false 
   return counter == 0
