lottery  = "hello coders"
# 'h' or 'e' or 'l' or 'l' or 'o'
print("choose correct character of the word '",lottery,"' to win  lottery")
inputs = input(" ")

if inputs == lottery[0].lower() or inputs == lottery[1].lower() or inputs == lottery[4].lower() or inputs == lottery[6].lower() or inputs == lottery[8].lower():
    print("sorry,you din't win thwe lottery")
else:
    print("congrats you win the lottery")
