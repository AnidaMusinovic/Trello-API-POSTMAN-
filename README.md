This is a project that includes the identification and automation of smoke test cases for Trello API. I used Postman to automate test cases.


# Below are test cases that I identified as smoke:

- Create a board
- Create a new list
- Create a new card
- Move card to another list
- Add a member to a card
- Add a member to a board
- Archive a list
- Delete a board
- Delete a card

# How to run the tests using newman

First, you have to download Trello collection and environment to your computer.
1. Open the terminal and type the command “newman run”
2. Drag the Trello collection document to the terminal 
3. Type “-e” command
4. Drag the Trello environment document to the terminal and click enter
