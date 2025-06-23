🐍 Snake Game 
A classic Snake game implemented in Java, using Swing and AWT for the graphical interface. The player controls a snake that grows in length by eating apples. The game ends when the snake hits the wall or collides with itself.


Technologies Used
Java 8 

Swing (javax.swing)

AWT (java.awt)

Image rendering via ImageIcon


How to Run
Requirements
Java Development Kit (JDK) version 8+
Optionally, an IDE like IntelliJ IDEA or Eclipse
 Compile & Run via Terminal
bash
Копиране
Редактиране
javac -d out src/projects/*.java
java -cp out projects.Snake
Alternatively, open the project in an IDE and run Snake.java.


 Controls
Key	Action
←	Move left
→	Move right
↑	Move up
↓	Move down


Features
Snake grows when eating apples
Game over on wall or self collision
Image-based snake and apple rendering
Smooth animation using a Swing timer
No external libraries required
