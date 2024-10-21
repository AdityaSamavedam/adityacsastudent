---
layout: base
title: Flashcards for CB units
description: Flashcards in HTML, CSS, & JS
hide: true
permalink: /flashcardstest
---

<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 1 Key Points</p>
        </div>
        <div class="back">
            <p>- Primitive Types: int, char, double, boolean (lowercase)<br>
               - Reference Types: Arrays, Strings, Objects, Classes (uppercase)<br>
               - Wrapper Classes: Turn primitives into objects<br>
               - Memory Allocation:<br>
                    &emsp; &emsp; - Stack Memory: Stores temp variables (primitives and object references), LIFO<br>
                    &emsp; &emsp; - Heap Memory: Stores objects and arrays (dynamic memory)<br>
               - Primitive Passing: Doesn't change the caller's value<br>
               - Wrapped Primitives: Allows modification of the original</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 2 Key Points</p>
        </div>
        <div class="back">
            <p> - Object: Created from a class<br>
                - Class: Blueprint for objects; groups attributes<br>
                &emsp; &emsp; - Constructor: Special function to create instances<br>
                &emsp; &emsp; - New: Creates a new object<br>
                &emsp; &emsp; - This: Refers to class variables<br>
                &emsp; &emsp; - Void Method: No return type<br>
                - Method Signature: Defines how a method behaves before implementation<br>
                - Java Method Parameters:<br>
                &emsp; &emsp; - Rule 1: Passed in order<br>
                &emsp; &emsp; - Rule 2: Separated by commas<br>
                &emsp; &emsp; - Rule 3: Include datatype and name<br>
                &emsp; &emsp; - Rule 4: Referenced by name inside method<br>
                - Non-Void Method: Returns a value (int, string, etc.)<br>
                - Escape Sequence: "\" used for formatting<br>
                - String Methods: length(), substring(), indexOf(), equals(), compareTo()<br>
                - Wrapper Classes: Turn primitives into objects</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 3 Key Points</p>
        </div>
        <div class="back">
            <p> - Java Relational Operators:<br>
                &emsp; &emsp; - equal to: ==<br>
                &emsp; &emsp; - not equal to: !=<br>
                &emsp; &emsp; - less than: <<br>
                &emsp; &emsp; - greater than: ><br>
                &emsp; &emsp; - less than or equal to: <=<br>
                &emsp; &emsp; - greater than or equal to >=<br>
                - Else statement purpose: handles what happens if condition is false<br>
                &emsp; &emsp; - If-Else statement structure:<br>
                        &emsp; &emsp; &emsp; &emsp; if (condition) {<br>
                           &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;  // do something<br>
                       &emsp; &emsp; &emsp; &emsp;  }<br>
                        &emsp; &emsp; &emsp; &emsp; else {<br>
                            &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; // do something else<br>
                        &emsp; &emsp; &emsp; &emsp; }<br>
                - Else If statements purpose: handling multiple conditions<br>
                - Nested Conditional statement: statement inside statement<br>
                - Compound Conditional statement: 2 or more conditions are combined into a single if statement (using logical operators)<br>
                - && (AND): (returns true only if both conditions are true)<br>
                - || (OR): (returns true if at least one condition is true)<br>
                - ! (NOT): Negation of statement</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 4 Key Points</p>
        </div>
        <div class="back">
            <p>- While loops: run until condition is false<br>
                &emsp; &emsp; - Syntax:<br>
                &emsp; &emsp; while (i < value) {<br>
                &emsp; &emsp; &emsp; &emsp; // do something<br>
                &emsp; &emsp; &emsp; &emsp; i++;<br>
                &emsp; &emsp; }<br>
                - Similarly, for loops run until condition is false<br>
                &emsp; &emsp; - Syntax:<br>
                &emsp; &emsp; for (i = minValue,i < maxValue, i++) {<br>
                &emsp; &emsp; &emsp; &emsp; // do something<br>
                &emsp; &emsp; }<br>
                - For each loop: used for iterating through items in a list:<br>
                &emsp; &emsp; - Syntax:<br>
                &emsp; &emsp; for (int element : list) {<br>
                &emsp; &emsp; &emsp; &emsp; // do something<br>
                &emsp; &emsp; }<br>
                - Iteration of index through string requires charAt(i)<br>
                - substring method divides string at provided starting/ending index values<br>
                - .split() splits a string into array based on what is provided in the argument and where it occurs in the string.</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 5 Key Points</p>
        </div>
        <div class="back">
            <p> - Class Declaration: starting point of any class. Includes class keyword, class name, and access modifiers.<br>
                - Instance Variables: attributes of class, declared inside class but outside any methods, normally set as private<br>
                - Constructor: special method called when an object is instantiated, no return type<br>
                &emsp; &emsp; - Default constructor: constructor w/o parameters, defined by compiler automatically if not defined<br>
                &emsp; &emsp; - Overloaded constructor/Parameterized constructor: constructor that accepts parameters to initialize fields<br>
                &emsp; &emsp; - No-arg constructor: no parameters, defined by a programmer<br>
                - Methods: define behaviors of class:<br>
                &emsp; &emsp; - Accessor: (getters): retrieve field values<br>
                &emsp; &emsp; &emsp; &emsp; - allows other objects to obtain the value of instance or static variables<br>
                &emsp; &emsp; &emsp; &emsp; - toString accessor Method: overriden method used to provide description of an object<br>
                &emsp; &emsp; - Mutator: (setters): modify/set field values<br>
                - Types of methods:<br>
                &emsp; &emsp; - Instance Methods: Methods that belong to an instance of a class Instance methods require an object of the class to be used. They operate on objects of the class.<br>
                &emsp; &emsp; - Can access instance variables and other instance methods within the class<br>
                &emsp; &emsp; - Can access static variables and methods<br>
                - "this" keyword: references object itself or object's instance variables, methods, constructors, etc.</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 6 Key Points</p>
        </div>
        <div class="back">
            <p> - Arrays: collection of primitive or object reference data<br>
                &emsp; &emsp; - length has datatype public final because it can be accessed anywhere and cannot be changed<br>
                &emsp; &emsp; - negative indexing does not work in Java<br>
                &emsp; &emsp; - cannot add or remove elements<br>
                &emsp; &emsp; - updating element values is allowed<br>
                &emsp; &emsp; - default values when an array is instantiated<br>
                - You can traverse through arrays using for loop or for each loop:<br>
                &emsp; &emsp; - Syntax for "for" loop:<br>
                &emsp; &emsp; for (int i = 0, i < array.length, i++) {<br>
                &emsp; &emsp; &emsp; &emsp; System.out.println(i);<br><br>
                &emsp; &emsp; }<br>
                &emsp; &emsp; - Syntax for "for each" or "enhanced for" loop:<br>
                &emsp; &emsp; for (i : array) {<br>
                &emsp; &emsp; &emsp; &emsp; System.out.println(i);<br>
                &emsp; &emsp; }<br>
                - Can traverse using while loops as well</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 7 Key Points</p>
        </div>
        <div class="back">
            <p>- ArrayList: resizeable array, can add or remove elements since length is not final<br>
                - Requires use of import statement: import java.util.ArrayList;<br>
                - Initializing ArrayList example: ArrayList&lt;Integer&gt; numbersList = new ArrayList&lt;&gt;();<br>
                - methods such as size, add, get, set, remove<br>
                - traverse with for loop, enhanced for loop, while loop<br>
                - Linear searching: iterates through whole list until target is found<br>
                - Selection sort: identifies either the maximum or minimum of the compared values and iterates over the structure checking if the item stored at the index matches that condition, if so, it will swap the value stored at that index and continue<br>
                - Insertion sort: inserts each value it finds at the appropriate location in the data structure</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 8 Key Points</p>
        </div>
        <div class="back">
            <p> - 2D array: array of arrays, created & indexed similar to 1D array<br>
                - Declaration of 2D array: int[][] 2DArrayName = new datatype[# of rows][# of columns]<br>
                - Use curly braces if you want to actually put values in the 2D array<br>
                - Each row of 2D array has its own initializer list<br>
                - Traversing 2D arrays:<br>
                &emsp; &emsp; - requires use of nested loops<br>
                &emsp; &emsp; - outer for loop: iterates through rows<br>
                &emsp; &emsp; - inner for loop: iterates through each value in the row<br>
                - Linear searching: iterates through whole list until target is found<br>
                - Binary searching: divide list repeatedtly in half (lower and upper half) until element is found, requires less steps than linear search<br>
                - Global sorting steps:<br>
                &emsp; &emsp; - create 2D array<br>
                &emsp; &emsp; - flatten 2D array (use nested loops to copy elements from 2D array into 1D array)<br>
                &emsp; &emsp; - sort 1D array<br>
                &emsp; &emsp; - reshape back into 2D array<br>
                &emsp; &emsp; - print out 2D array</p>
        </div>
    </div>
</div>
<div class="flashcard-container">
    <div class="flashcard" onclick="flipCard(this)">
        <div class="front">
            <p>Unit 9 Key Points</p>
        </div>
        <div class="back">
            <p> - Inheritance Basics: Allows subclass to inherit properties and behaviors from superclass; promotes code reuse.<br>
                - Superclass: Parent class; provides attributes and methods to subclasses.<br>
                - Subclass: Inherits from superclass; can extend or override methods, add new attributes.<br>
                - Method Overriding: Subclass modifies inherited methods from the superclass.<br>
                - Polymorphism: Subclass objects treated as superclass instances; dynamic method calls at runtime.<br>
                - super Keyword: Refers to superclass; used to access superclass constructor or overridden methods.<br>
                - Object Class: Root of Java class hierarchy; all classes inherit from it.<br>
                - Class Hierarchies: Multi-level inheritance creates complex class relationships.<br>
                - Overriding vs Overloading: Overriding changes method behavior in subclass; overloading uses same method name with different parameters.<br></p>
        </div>
    </div>
</div>
<style>
            * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        padding: 20px;
    }
    header {
        text-align: center;
        margin-bottom: 20px;
    }
    .flashcard-container {
        perspective: 1000px;
        display: grid;
        gap: 20px;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        width: 100%;
        max-width: 900px; /* Set a maximum width to center the container */
        margin: 0 auto; /* Centers the flashcard container */
        padding: 20px;
        justify-content: center; /* Align items to the center of the container */
    }
    .flashcard {
        width: 800px;
        height: 800px;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        position: relative;
        transform-style: preserve-3d; /* Ensure both sides are preserved */
        transition: transform 0.6s;
        cursor: pointer;
    }
    .flashcard.flip {
        transform: rotateY(180deg); /* Rotate the card to show the back side */
    }
    .front, .back {
        position: absolute;
        width: 100%;
        height: 100%;
        backface-visibility: hidden; /* Hide the back when flipped */
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 18px;
        padding: 20px;
        border-radius: 10px;
        overflow-y: auto;
    }
    .front {
        background-color: #4CAF50;
        color: white;
        text-align: center;
    }
    .back {
        background-color: #2196F3;
        color: white;
        transform: rotateY(180deg); /* Rotate the back side so it's hidden initially */
        text-align: left;
    }
</style>
<script>
    function flipCard(card) {
    card.classList.toggle('flip');
}
</script>

<script src="https://utteranc.es/client.js"
        repo="AdityaSamavedam/adityacsastudent"
        issue-term="pathname"
        theme="github-dark"
        crossorigin="anonymous"
        async>
</script>