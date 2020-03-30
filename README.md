## Tic Tac Toe
---

### About  
Tic-Tac-Toe mobile game made with React Native mobile application framework. The app runs on both Android & iOS.  
It is a multiplayer game, players have to play by alternative turns. Game can be reset anytime using the Reset button. It automatically resets when a game is finished and display the win/draw message.  
Any circle or cross cannot be overwritten once played.

---

### Working
* Array is used to maintain state of Tic Tac Toe blocks ("cross", "circle" or "empty").
* When a player taps on a block check what state it is in, then update the state and display the corresponding image from the assets.
* Asynchronously call the win() logic and check if anybody has won or the game is drawn.
* If won/drawn, display the approriate message and reset the game (remember to reset the array used for maintaining state).
* Anytime Reset Button is pressed, reset the game.  

##### Requirements:  
* [Node.js](https://nodejs.org/en/)
* [Expo CLI](https://docs.expo.io/versions/latest/workflow/expo-cli/)  
* Any Text editor, I have used [VS Code](https://code.visualstudio.com/)  
 
---

### Installation  
1. Clone the repository and navigate into the folder.
   ```bash
   $ git clone https://github.com/rishabhsxn/TicTacToe_ReactNative.git   
   ```         
2. Install the dependencies using npm.     
    ```bash
   $ npm install   
    ```  
3. To run the application on expo, execute the command   
    ```bash
   $ npm start   
    ```   
---

### Demo  
![TicTacToe Demo](https://media.giphy.com/media/UtVuveY1oJHt29O57T/giphy.gif)
