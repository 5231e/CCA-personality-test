# CCA-personality-test
 <<<<<<< main
Are you having trouble finding a CCA? Come take this quiz to find out what CCA best suits you!
print("Title of program: CCA Matching Personality test")
print()
print("Welcome to DHS! We hope you had  geat impression of our school. Please answer the following questions truthfully and we'll suggest a CCA for you! We will chose the best one so that you will enjoy your dunman high experience here!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

tech1 = input("I enjoy building and fixing things.")

outdoor1 = input("I'll go crazy if I do not go out of the house for the whole day.")

music1 = input("I can hear a story in my mind whenever i hear music.")

tech2 = input("I know/have interest in building apps and websites.")

outdoor2 = input("I'm good at and enjoy tying knots and ropes.")

music2 = input("I have an interest in a musical instrument.")


tech_final = int(tech1) + int(tech2)
outdoor_final = int(outdoor1) + int(outdoor2)
music_final = int(music1)+ int(music2)

print()

if tech_final > outdoor_final and tech_final > music_final:
  print("You might be suitable for Infocomm club!")
elif outdoor_final > music_final:
  print("You might be stuiable for ODAC or an uniformed group!")
else:
  print("You might be suitable for a CCA from performing arts!")

  
=======
Clarisse's personality test :)
 >>>>>>> main
