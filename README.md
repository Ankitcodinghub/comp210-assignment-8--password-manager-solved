# comp210-assignment-8--password-manager-solved
**TO GET THIS SOLUTION VISIT:** [Comp210 Assignment 8- Password Manager Solved](https://www.ankitcodinghub.com/product/comp210-password-manager-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131782&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp210 Assignment 8- Password Manager Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
In this assignment you will be implementing a version of a HashMap in order to create your own password manager.

A password manager is an application designed to store and manage someone’s passwords. The #1 rule of password security is to not reuse passwords, we all know that whenever safari or chrome recommends those strong password filled with random letters and numbers, no one actually uses them. However with a password manager, you can use strong passwords because you don’t have to remember them. All it takes is 1 master password for the password manager, and then you can access all of your stored passwords.

HashMap

Input Output

The interface for the password manager will be a command line application that uses a Scanner to read inputs. The code for the input output logic should all go in the main method in Main.java. The Scanner and Password Manager object are already created for you. Upon running your program, your password manager should print “Enter Master Password”. Change the value of the variable MASTER_PASSWORD in

PasswordManager.java to any String of your choosing. If the entered password does not match the password saved in the

MASTER_PASSWORD variable, reprint “Enter Master Password” until the correct password is entered. Once they are given access, the user should be able to enter one of the following phrases: “New password”, “Get password”, “Delete account”, “Check duplicate password”,”Get accounts”, “Generate random password”, or “Exit”. If something other than these 7 phrases are entered, print “Command not found” and wait for another command. After each case, excluding “exit”, they can enter another phrase. If they enter exit, they get reprompted to enter the master password. Here is a link to a control flow diagram to help visualize the logic: https://drive.google.com/file/d/1XqckgFA8S3Zo1TPz826N5InO0JAGLk3/view?usp=sharing

Based on which phrase is entered, you should call one of the methods in your password manager using the entered parameters. For each command, the user should be able to input the command name, and the needed parameters in the correct order. Here are the guidelines for using commands with parameters. “Get accounts” and “Exit” do not have any parameters. New password: input: New password Website Name Password output: New password added

Get password input: Get password Website name output: Password does not exist || the account’s password Delete account input: Delete Account Website name output: Account deleted || Account does not exist

Check duplicate password input: Check duplicate password password output: No account uses that password || Websites using that password: website1 website2 Get accounts input: Get accounts output: Your accounts: account1 account2 account 3 etc.

Generate random password input: Generate random password Length of password (should be an int) output: generated password

Below is an example of the expected inputs and outputs, where the master password is password123. The bold represents what is printed and the normal text is what the user enters.

Enter Master Password password Enter Master Password password123 New password facebook mypassword New password added New passsword instagram mypassword New password added fake command Command not found Get password facebook mypassword Get password twitter Account does not exist Check duplicate password mypassword Websites using that password: facebook instagram Check duplicate password password789 No account uses that password Generate random password 10

Zq9CZ9noe4 New password facebook Zq9CZ9noe4 New password added Get accounts Your accounts: facebook instagram Delete

account facebook Account deleted Delete account snapchat Account does not exist Exit Enter Master Password
