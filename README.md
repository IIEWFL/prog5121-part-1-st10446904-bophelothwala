Name: Bophelo Thwala 

 

Student No.: ST10446904 

 

Module Code: PROG5111 

 

Lecturer: Mr. Steven Ndaye 

 

PROGRAMMING 1A – POE part 1 

 

 

 

 

 

 

 

 

 

Chat App – part 1 

 

Part 1: User Authentication 

 

A list of options will display, you can enter a number, you can enter a number based on the options given e.g. user press 1 => 1. Register 

           Options: 

          1. Register 

          2. Login 

         3. Check Users 

        0. Exit App 

 

The user has the option to exit the app by pressing 0 

 

The user has the option to press 3 to verify if any usernames were stored 

 

 

Registration 

 

The user will be prompted to enter user details such as (username, password and cellphone number) 

 

Measures have been placed to ensure the user cannot skip any registration steps such as 

              - Making sure the user has entered something 

                   If username == null or password == null or cellphoneNumber == null 

                        Output “Make sure you have entered all the details” 

             - Followed the username conditions (less than 5 characters and has an underscore) 

 

       - Followed the password conditions (have 8 to 16 characters, a capital letter, a number and a special character). 

      - Followed the cellphone number conditions (has an international code, no more than 10 characters). 

    

 

Login 

The user will be prompted to enter user details used in the registration process. 

 

Measures have been placed to ensure the user cannot skip any login steps such as 

              - Making sure the user has entered something 

                    If inputUsername == null or inputPassword == null or inputCellphoneNumber == null 

                       Output “You did not enter anything” 

             - The entered username matches the registered username 

                   If inputUsername != user1.getUsername() 

                       Output “Username does not exist” 

       

             - The entered password matches the registered password. 

                   If inputUsername != user1.getPassword() 

                       Output “Incorrect password” 

 

           - The cellphone number entered matches the registered cellphone number. 

 

              If inputUsername != user1.getCellPhoneNumber() 

                       Output “Incorrect phone number” 

 

 

Codes of the chat app poe part 1 in java is available at: 

https://github.com/IIEWFL/prog5121-part-1-st10446904-bophelothwala.git 

 

 

Reference list 

 

AI used: Claude 

 

My prompt: Can you show me an example how to check if a user has correctly followed these conditions when registering or loggin in with these conditions: Password - Must contain a capital letter, a number, a special character, cellphone number - it must start with country code in java 

 

Anthropic. (2025). Claude 3.7 Sonett (Feb 19 version) [Large language model]. 

https://claude.ai/new 
