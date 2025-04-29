# csed332-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSED332  Assignment 1 Solved](https://www.ankitcodinghub.com/product/csed332-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115987&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED332 &nbsp;Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Objectives

• Make sure you can install and run IntelliJ IDEA.

• Create your GitLab account on https://csed332.postech.ac.kr.

• Use Maven

• Learn Java programming language

Getting Java

• We will use IntelliJ IDEA in this class. You will need Java, or more specifically, the Java Development Kit (JDK). Get the latest JDK (16.0.2) from:

https://www.oracle.com/technetwork/java/javase/downloads

Getting IntelliJ IDEA

https://www.jetbrains.com/idea/download

Microsoft Teams

• Leave any message in the Homework1 channel.

Create your GitLab account

• Create your GitLab account using your Hemos ID and your name in English (the same as those in POVIS) at the GitLab repository server

https://csed332.postech.ac.kr

• Create SSH keys, following https://csed332.postech.ac.kr/help/ssh/README.

• Create a private project with name homework1, and clone the project to your machine.

Problem 0: Short Questions

• Create an unformatted text file named README.md in homework1 (on your machine).

• Write your answers for the IntelliJ IDEA questions below. Format the text using the Markdown language (https://daringfireball.net/projects/markdown).

1. You find a piece of code on the web. You copy it into IntelliJ IDEA but the formatting is off. Using IntelliJ IDEA shortcuts, how would you change the unformatted text:

public class HelloWorld {

public static void main(String[] args) { System.out.println(“Hello World”);

} }

into the formatted text below?

public class HelloWorld { public static void main(String[] args) {

System.out.println(“Hello World”);

}

}

2. Sometimes you would like to quickly comment/uncomment a chunk of code. How would you do this (i.e., what keyboard shortcut would you use) in IntelliJ IDEA without having to manually manipulate each line?

3. Keyboard shortcuts are useful when you are editing Java code. One very useful keyboard shortcut is ctrl + Alt + B (or + + B in Mac). What does it do?

• Add and commit the changes, and upload them to the remote repository. You should be able to see your answers at the front page of your homework1 project.

IntelliJ IDEA

1. Answer1

2. Answer2

3. Answer3

IntelliJ IDEA and Maven

• Download the attached file homework1.zip, which contains two subdirectores problem1 and problem2. Each of them can be imported as a separate project into IntelliJ IDEA.

• In this assignment, your code need to be compiled using only Maven in a command line. You can use IntelliJ IDEA, but your code will be graded using Maven.

• To compile your code using Maven, you can go to where your pom.xml is for each problem, and execute the command mvn compile. You can run mvn test to run test cases.

Problem 1

• The goal is to create a simple account management system for banking as follows. Check more detailed information in the skeleton code.

– A bank manages two kinds of accounts: high-interest and low-interest accounts, where a high-interest account has a minimum balance.

– Each account has an account number and an owner. You can deposit or withdraw money from an account, and transfer money from one account to another account.

• The src/main directory contains the skeleton code. You should implement all methods with TODO in the following classes:

– Bank

– HighInterestAccount

– LowInterestAccount

• The src/test directory contains some test methods in BankTest.java. You can run the test cases by running mvn test.

• Your code will be graded by Maven, using extra test cases (different from BankTest.java) written by teaching staff. Make sure the command mvn test works.

• Do not modify the existing interfaces, the class names, and the signatures of the public methods. You can add more methods or classes if you want.

Problem 2

• The goal is to implement a mini tower-defense game. As shown in the following figure, a game board contains a number of monsters and towers.

– A game board consists of n×m tiles, and the position of each tile is given by a pair (x,y), where 0 ≤ x &lt; n and 0 ≤ y &lt; m.

– (x,y) and (x′,y′) are adjacent iff (i) x = x′ and |y − y′| = 1, or (ii) |x − x′| = 1 and y = y′. E.g., (2,3) and (1,3) are adjacent, but (2,3) and (1,2) are not adjacent.

– Monsters move towards the goal tile (marked as a green square). There are two types of monsters: ground monsters and flying monsters.

– Towers attack (or kill) all adjacent monsters. There are two types of towers: air towers only attack flying monsters, and ground towers only attack ground monsters.

– Two flying monsters cannot be on the same tile. Similarly, two ground objects (ground towers, air towers, or ground monsters) cannot be on the same tile.

• A game consists of a number of rounds. For each round, monsters and towers perform actions as follows, and the game proceeds to the next round.

1. All monsters on the goal tile “escape” from the game board.

2. Each tower attacks (and removes) all adjacent monsters of its type.

3. The remaining monsters (neither escaped nor attacked) can move to an adjacent tile.

• In this assignment, you implement an object-oriented “model” of the game described above, given by the following classes.

– GroundTower and AirTower implements the interface Tower, with the method attack that returns the set of monsters to be attacked by this tower in the current round.

– GroundMob and AirMob implements the interface Monster, with the method move that returns an adjacent position to be moved for the next round.

– GameBoard maintains a set of towers and monsters, and contains several methods for the game, such as the method step that runs a single round of the game.

• A simple monster AI will be defined and implemented by students as a part of this assignment (the move method of GroundMob and AirMob).

– The game should not fall into error states (e.g., two ground objects are on the same tile) by monster movements. See the method isValid of GameBoard.

– Each monster should try to reach the goal tile as soon as possible, avoiding being attacked by towers, and not falling into error states.

– For example, consider Board 0 below. Each monster can move to an adjacent tile or stay on the current tile in the next round. Consider three possible movements:

∗ Board 1 is in an error state, because two ground monsters are on the same tile.

∗ Board 2 is in a valid state, but not optimal since one ground monster is killed.

∗ Board 3 is in a valid state and no monsters are killed by towers.

– We will run your strategy with respect to several game boards for grading. Students developing better strategies will receive additional bonus points.

• We provide a simple GUI that runs the game on your model. It will not be used for grading, but you can inspect your implementation using this GUI.

– The state of GameBoard is displayed in the GUI panel.

– The Next button runs the method step of GameBoard.

– If the game falls into an error state, Next will be disabled.

– The Randomize button generates a new random game.

• The src/main directory contains the skeleton code. You should implement all classes and methods with TODO in the above classes.

• The src/test directory contains some test methods in GameTest.java. Your code will be graded by Maven, using extra test cases written by teaching staff.

• The command mvn package will create a jar file in the target directory, which can be executed using the command: java -jar problem2-1.0-SNAPSHOT-shaded.jar

• Do not modify the existing interface, the class names, and the signatures of the public methods, as they are used for the GUI and for grading.

Turning In

1. Commit your changes in your homework1 project that includes two directories problem1 and problem2, and push them to the remote repository.

2. Tag your project with “submitted” and submit your homework. We will use the tagged version of your project for grading.

Java Reference

• Java Language Specification: https://docs.oracle.com/javase/specs/
