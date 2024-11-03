# Changing the server repo
For a custom version of the game, to change the server repo the game gets these assets from, find the blue flag script in the stage sprite and change the set server repo block to the URL of your fork.

![block_11_3_2024-3_29_37 AM](https://github.com/user-attachments/assets/03b3350e-3532-4de4-ab87-1d8d7398d9cc)

# Adding new text, menu buttons and on screen art
Each of these sprites have a custom block to help you do this!

![block_7_26_2024-2_15_37 PM](https://github.com/user-attachments/assets/f9b60511-bdd1-4ed4-acb1-1f490102375d)
![block_7_26_2024-2_16_14 PM](https://github.com/user-attachments/assets/a62a628f-c4ab-4c34-b370-ab831bb1e5ba)
![block_7_26_2024-2_16_51 PM](https://github.com/user-attachments/assets/1bf2433f-8675-429d-8c1f-07f273aec07e)
![block_7_26_2024-2_17_03 PM](https://github.com/user-attachments/assets/08df3217-4109-4e19-935d-298163644029)

To check out the state of the game, press the 1 key to show the state and substate variables.

# Adding new scripts to the game
Every time the state of the game switches, it uses state and substate variables. When the variables are changed, messages like state sync and substate sync are broadcasted. To add a new script for when a state starts, do something like this:

![block_7_26_2024-2_22_55 PM](https://github.com/user-attachments/assets/62e9ee13-fe1d-456a-b3fb-870ce75f407f)

To change the state of the game, simply change the state variable, and you can also do the same with substates. The needed messages are automatically broadcasted.
