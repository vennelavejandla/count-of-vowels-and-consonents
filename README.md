# count-of-vowels-and-consonents
s=input()
v="aeiouAEIOU"
c=0
l=0
for i in range(len(s)):
  if s[i].isalpha:
    if s[i] in v:
      c=c+1
    else:
      l=l+1
print(c,l )
