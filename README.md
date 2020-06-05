![Python](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.-XML4trl5z0eloWJfwkeMAHaDt%26pid%3DApi&f=1)

## This is the Wissensbar Calculator!
---

*Any idea what this means? No?* Don't worry - it is my job to explain that to you. 
The **Wissensbar Calculator** is a calculator that calculates the area of a circle when the user has given it the radius of that circle. *Does not seem very interesting does it?* Let me tell you that you think right: it's not very cool or stuff, and in the current version of the project, it even uses that console that is inbuilt into your computer... Gee! Weird, is it not?

**BUT THAT IS THE VERY REASON THAT YOU SHOULD USE IT!**

Most people use lots of applications that they download from the internet. To a person not very professional at computers, this may seems like a hard thing. You have to download it, run an Installation Wizard, choose a place to locate it while downloading, and lots of other stuff that may seem very mundane and irritating. Well guess what - **you're in luck!**

This calculator has been created for people that want to calculate the area of a circle, but don't want to waste their precious time on calculations that are seemingly insignificant to your lives. Why would one calculate something unless he absolutely had to? I would not, for that is nothing but a waste of my valuble time! Why not let a computer that likes to do this kinda stuff do it? 
Suppose you had a friend who loves eating eggplant, but (I take the liberty of presuming that) most of us don't, do we? So, if on a picnic someone had the audacity to bring an eggplant sandwich, why not give it to him? He likes it and you don't! Everyone is happy!

---
Another thing that people like is the raw look of [Command Line Interfaces](https://en.wikipedia.org/wiki/Command-line_interface). So, I decided to incorporate that into my project, and give the user a feel of using a real command line. It even uses user inputs like '*y*' and '*n*' from the user, similar to what Linux does to its users when they try to install software using the [Linux Console](https://en.wikipedia.org/wiki/Linux_console). 

Below I am showcasing some of the code in the program.

```py
def consequent_calculator(): # This functions is following the main part of the calculator and checks if the user wants to calculate more areas. 
    while True:
        check1 = str(input("Type in 'y' to calculate another circle's area or 'q' to quit:  "))
        if check1 == "y":
            print("")
            circle_area_calc()
        elif check1 == "q":
            quit_check = str(input("If you quit, then you will have to restart the machine. Are you sure that you want to quit? (y/n): "))
            if quit_check == "y":
                sys.exit() # This states that if the user input's 'n', then the program will self kill
            elif check1 == "n":
                print("")
                pass
            else:
                print("Error! Please check and try again.")
                print("")
                consequent_calculator()
        elif check1 != "y" or "n":
            print("")
            print("Error! Either 'y' or 'n'has to be entered.")
            consequent_calculator()
        else:
            print("")
            print("Error! Please do not enter any values other than 'y' or 'n'.")
            consequent_calculator()


consequent_calculator()

```

If you know **Python**, then you can see the simplicity of the code that has been written above. If you don't know *Python*, then let me tell you that this is very, very simple *Python*. It is therefore only logical that the program will not put much pressure on your computer. 

**Note:** Each boot-up may take upto fifteen seconds, but this has nothing to do with the computer's performance or quality, this happens because the project needs some time to get ready files and modules that you do not have on your computer. 

---
## Updates
When somebody downloads a program, what she or he wants to see is that the packages and modules are regularly updated. If they do not get updates, then they are not viable and good for an in the long run. 

I love coding and spend a lot of time doing so, and therefore, I will most definitely keep updating the Wissensbar Calculator, and in the process, make it more user-friendly and I will also add more features and stuff to it. The Wissensbar Calculator is also one of the first *Python* projects that I have started in a long while, and I intend to keep it running and updating it as much as possible. 
I will keep updating the program so that it becomes more and more user-friendly and more like a Command Line. 

 ---

![Programming](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ne876PVNQzu5OyhDh1xDvwHaEK%26pid%3DApi&f=1)
