# Use of Custom Functions & Error Checking/Restrictions

The concept I implemented was custom functions with restrictions, which help control user input and prevent invalid actions. One example is the drawButton() method:

<img width="460" height="108" alt="image" src="https://github.com/user-attachments/assets/3222e816-9709-4285-9dc7-912db08335d8" />

This function was used throughout the game to draw interactive buttons and visually indicate when they are clickable. I implemented it to reduce repeated code and to standardize button behavior. A challenge I faced was making sure buttons responded correctly across different screens. I fixed this by reusing the same function everywhere and relying on collision detection to restrict when interactions are allowed.
