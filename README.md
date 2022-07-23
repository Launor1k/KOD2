s='ГЕКЛО'
count=0
min=1000000000
for q in s:
   for w in s:
      for e in s:
         for r in s:
            for t in s:
               i=q+w+e+r+t
               count+=1
               if (i.count('Л')==2) and (count >20):
                  if count < min:
                     min=count
print(min)
