# This is the Wissensbar Calculator! ✔

**This is the Wissensbar Calculator!** *Any idea what this means? No?* Don't worry - it is my job to explain that to you.

The **Wissensbar Calculator** is a calculator that calculates the area of a circle when the user has given it the radius of that circle. *Does not seem very interesting does it?* Let me tell you that you think right: it's not very cool or stuff, and in the current version of the project, it even uses that console that is inbuilt into your computer... Gee! Weird, is it not? Yeah! Of course, people!!!

## 🚀 | **BUT THAT IS THE VERY REASON THAT YOU SHOULD USE IT!**

Most people use lots of applications that they download from the internet. To a person not very professional at computers, this may seems like a hard thing. You have to download it, run an Installation Wizard, choose a place to locate it while downloading, and lots of other stuff that may seem very mundane and irritating. Well guess what - **you're in luck!**

This calculator has been created for people that want to calculate the area of a circle, but don't want to waste their precious time on calculations that are seemingly insignificant to your lives. Why would one calculate something unless he absolutely had to? I would not, for that is nothing but a waste of my valuble time! Why not let a computer that likes to do this kinda stuff do it? 
Suppose you had a friend who loves eating eggplant, but (I take the liberty of presuming that) most of us don't, do we? So, if on a picnic someone had the audacity to bring an eggplant sandwich, why not give it to him? He likes it and you don't! Everyone is happy!

--- 

Another thing that people like is the raw look of [Command Line Interfaces](https://en.wikipedia.org/wiki/Command-line_interface). So, I decided to incorporate that into my project, and give the user a feel of using a real command line. It even uses user inputs like '*y*' and '*n*' from the user, similar to what Linux does to its users when they try to install software using the [Linux Console](https://en.wikipedia.org/wiki/Linux_console). In the more recent 1.1.0 and above releases, the editions have a color coding for the user interface, thus enhancing the experience of using it and making it look awesome! [Click here to read about this edition](https://github.com/sankar-1776/Wissensbar#latest-release).

---

## Some Code From This Program: 

Below I am showcasing some of the code in the program.

```py
# The following function will be used to check if the user wants to calculate the areas of further circles and then loop him/her back to circle_area_calc().
    
def consequent_calculator():
        while True:
            check1 = str(input(gyellow + "Wissensbar # " + end + red + "Type in 'y' to calculate another circle's area or 'q' to quit" + end + result + " %%>>> " + end))
            print("")
            if check1 == "y" or "Y":
                print("")
                circle_area_calc()
            elif check1 == "q" or "Q":
                quit_check = str(input(error + "If you quit, then you will have to restart the machine. Are you sure that you want to quit? If yes, then enter 'y' and hit enter, if not, then hit 'n' and then enter" + end + result + " %%>>> " + end))
                if quit_check == "y":
                    sys.exit() # This states that if the user input's 'n', then the program will self kill
                elif quit_check == "n" or "N":
                    print("")
                    pass
                else:
                    print(error + "Sorry! This is not an accepted command. Please check and try again." + end)
                    print("")
                    consequent_calculator()
            elif check1 == "t" or "T":
                deck_()
            elif check1 != "y" or "Y" or "n" or "N":
                print("")
                print(error + "ERROR! Either 'y' or 'n' has to be entered." + end)
                consequent_calculator()
            else:
                print("")
                print(error + "ERROR! Please do not enter any values other than 'y' or 'n'."+ end)
                consequent_calculator()


consequent_calculator() # This will run the function to repeatedly to check if the user wants to calculate the area of further circles (consequent_calculator).

```
 > The above code is based on v1.0.2
 
---

If you know **Python**, then you can see the simplicity of the code that has been written above. If you don't know *Python*, then let me tell you that this is very, very simple *Python*. It is therefore only logical that the program will not put much pressure on your computer. 

**Note:** Each boot-up may take upto ten seconds, but this has nothing to do with the computer's performance or quality, this happens because the project needs some time to get files and modules that you do not have on your computer up and running. 

---
## 👋 | About Updates:
When somebody downloads a program, what she or he wants to see is that the packages and modules are regularly updated. If they do not get updates, then they are not viable and good for an in the long run. 

I love coding and spend a lot of time doing so, and therefore, I will most definitely keep updating the Wissensbar Calculator, and in the process, make it more user-friendly and I will also add more features and stuff to it. The Wissensbar Calculator is also one of the first *Python* projects that I have started in a long while, and I intend to keep it running and updating it as much as possible. 
I will keep updating the program so that it becomes more and more user-friendly and more like a Command Line. 

### Latest Release:
The latest version of the Wissensbar Calculator is the 1.1.3 release. It has come with some major upgrades and I've also introduced a style for the user to navigate the console. You can use some special commands to navigate it. For now, the commands are not much, and I will be listing them below for your reference. 


 #### Using The Wissensbar Calculator:
> Use the command **cr_calc.init{1}** to initiate the Calculator part of the **Wissensbar Calculator**
 
> Use the command **help.disp{0}** to read a small help dialogue.

> Use the command **shtdn.op{A}** to use the **Wissenbar OS** to shutdown your computer.

> Use the command **restrt.op{A}** to use the **Wissensbar OS** to restart your computer.

> Use the command **quitZ.op{1}** to to quit the **Wissensbar Calculator**.

> Use the command **webpg.open{0}** to open this webpage for references.

> Use the command **clear!** to clear your screen.

---

## Downloading the Wissensbar Calculator:
Have you ever come across a point in time when you hated installing a program onto the hard-drive of your computer? Frankly, I have. It can be irritating. So I said, don't install it! Why don't I create my project so that it can be installed without the user facing any problem of running a Setup Wizard, and stuff. 

So yeah! When you download the Wissensbar Calculator, just double click the application and you are on your way!!!

After downloading the Wissensbar Calculator, when running it for the first time, you may come accross a dialogue saying that Windows Protected You (if you are on a Windows), or a message saying that this may be an unsafe file by your computer. This goes to show that your computer is trying to keep you safe, and it's very good if this happens. What you should do if you are running Windows is click on **More Info** and then on **Run Anyway**. I assure you that this program has no virus or similar malware, and is composed only of Python code that calculates and improves the user interface. If you want more info on this, please email me at the emails given in the following part 😊.

---

## Contacting Me:
- You could also contact me at *iPython.org@gmail.com*; and
- Another email address of mine is sankar@sankarhk.com
    - sankar@sankarhk.com is currently facing some problems, but I'll let you know as soon as I can if it get's fixed. 

Please choose where to email to email me, but I would recomend you to do so to iPython.org@gmail.com. Thanks!

You could also visit my website [here](https://www.sankarhk.com/).

**NOTE:** If you do email me, then I will try my best to answer them as soon as I can. 

✔
