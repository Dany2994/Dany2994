- 👋 Hi, I’m @Dany2994, thank you for swinging by.
- 👀 I’m interested in learning artificial intelligence, and restaurants!
- 🌱 I’m currently learning Object Oriented Programming, and a bunch of cooking techniques. 
- 📫 Feel free to reach me at danywestern29@gmail.com, must include your favorite food!
- ⚡ Fun fact: I were a professional cook/chef and working habits at kitchen follows me at home, LABEL EVERYTHING!

Pro tip: 

def make_rice():
    while True:
        try:
            cup_rice = input("How many cups of rice do you have? ")
            cup_rice = float(cup_rice)
            if cup_rice.is_integer():
                cup_rice = int(cup_rice)
            break
        except ValueError:
            print("Use only numbers for cups!")
    cup_water = cup_rice * 2
    print(f"You'll need {cup_water} cups of water for those {cup_rice} cups of rice, make egg fried rice tomorrow!")
make_rice()

Beign a foodie is goodie.
