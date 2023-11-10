[# 45-Questions]
1
(https://nodejs.org/en/)https://nodejs.org/en/,https://www.typescriptlang.org/download,https://code.visualstudio.com/

2 // Store a person's name in a variable
let personName: string = "Eric";

// Print a personalized message
console.log(`Hello ${personName}, would you like to learn some Python today?`);

3 // Store a person's name in a variable
let personName: string = "Eric";

// Print in lowercase
console.log("Lowercase: " + personName.toLowerCase());

// Print in uppercase
console.log("Uppercase: " + personName.toUpperCase());

// Print in title case
console.log("Titlecase: " + toTitleCase(personName));

// Function to convert string to title case
function toTitleCase(str: string): string {
    return str.replace(/\w\S*/g, function(txt) {
        return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
    });
}

4 . // Store the quote and its author in variables
let quote: string = "A person who never made a mistake never tried anything new.";
let author: string = "Albert Einstein";

// Print the quote and its author
console.log(`${author} once said, "${quote}"`);

5. // Store the famous person's name in a variable
let famousPerson: string = "Albert Einstein";

// Store the quote in a variable
let quote: string = "A person who never made a mistake never tried anything new.";

// Compose the message
let message: string = `${famousPerson} once said, "${quote}"`;

// Print the message
console.log(message);

6. // Store a person's name with whitespace
let personNameWithWhitespace: string = "\t\n   John Doe   \t\n";

// Print the name with whitespace
console.log("Name with Whitespace: " + personNameWithWhitespace);

// Strip whitespace and print the cleaned name
let strippedName: string = personNameWithWhitespace.trim();
console.log("Stripped Name: " + strippedName);

7. // Addition
console.log("Addition: " + (5 + 3));

// Subtraction
console.log("Subtraction: " + (10 - 2));

// Multiplication
console.log("Multiplication: " + (4 * 2));

// Division
console.log("Division: " + (16 / 2));

8. console.log(4 + 4);
   console.log(10 - 2);
   console.log(2 * 4);
   console.log(16 / 2);

9. // Store your favorite number in a variable
let favoriteNumber: number = 7;

// Create a message revealing your favorite number
let message: string = `My favorite number is: ${favoriteNumber}`;

// Print the message
console.log(message);

10. // Famous Quote Program
// Author: [Your Name]
// Date: [Current Date]

// Store the famous person's name in a variable
let famousPerson: string = "Albert Einstein";

// Store the quote in a variable
let quote: string = "A person who never made a mistake never tried anything new.";

// Compose the message
let message: string = `${famousPerson} once said, "${quote}"`;

// Print the message
console.log(message);
 This program stores a famous person's name and a quote in variables, composes a message using a template string, and then prints the message to the console.
 // Number Eight Program
// Author: [Your Name]
// Date: [Current Date]

// Addition
console.log(4 + 4);

// Subtraction
console.log(10 - 2);

// Multiplication
console.log(2 * 4);

// Division
console.log(16 / 2);
This program demonstrates four different arithmetic operations, each resulting in the number 8, and prints the results to the console.

11. // Store the names of friends in an array
let names: string[] = ["Alice", "Bob", "Charlie", "David", "Eva"];

// Print each person's name one at a time
console.log("Names of Friends:");
console.log(names[0]);  // Print the first name
console.log(names[1]);  // Print the second name
console.log(names[2]);  // Print the third name
console.log(names[3]);  // Print the fourth name
console.log(names[4]);  // Print the fifth name

12. // Store the names of friends in an array
let names: string[] = ["Alice", "Bob", "Charlie", "David", "Eva"];

// Print a personalized message to each person
console.log("Greetings to Friends:");
console.log(`Hello, ${names[0]}! Have a great day.`);
console.log(`Hello, ${names[1]}! Have a great day.`);
console.log(`Hello, ${names[2]}! Have a great day.`);
console.log(`Hello, ${names[3]}! Have a great day.`);
console.log(`Hello, ${names[4]}! Have a great day.`);

13. // Store favorite modes of transportation in an array
let transportationModes: string[] = ["Tesla Model 3", "Harley-Davidson Motorcycle", "Bicycle", "Sailboat", "Private Jet"];

// Print statements about each item
console.log("My Favorite Modes of Transportation:");
console.log(`I would like to own a ${transportationModes[0]}.`);
console.log(`I dream of riding a ${transportationModes[1]}.`);
console.log(`A ${transportationModes[2]} is a great eco-friendly choice for short trips.`);
console.log(`Someday, I hope to sail on a ${transportationModes[3]}.`);
console.log(`Traveling in a ${transportationModes[4]} would be a luxurious experience.`);

14. // Store people to invite to dinner in an array
let guestList: string[] = ["Albert Einstein", "Ada Lovelace", "Leonardo da Vinci"];

// Print invitations to each person
console.log("Dinner Invitations:");

console.log(`Dear ${guestList[0]},\n\tYou are invited to dinner. Please join us for a delightful evening.`);
console.log(`Dear ${guestList[1]},\n\tYou are invited to dinner. Your pioneering work has inspired many.`);
console.log(`Dear ${guestList[2]},\n\tYou are invited to dinner. Your artistic genius continues to captivate the world.`);

15. // Store people to invite to dinner in an array
let guestList: string[] = ["Albert Einstein", "Ada Lovelace", "Leonardo da Vinci"];

// Print invitations to each person
console.log("Dinner Invitations (First Set):");

console.log(`Dear ${guestList[0]},\n\tYou are invited to dinner. Please join us for a delightful evening.`);
console.log(`Dear ${guestList[1]},\n\tYou are invited to dinner. Your pioneering work has inspired many.`);
console.log(`Dear ${guestList[2]},\n\tYou are invited to dinner. Your artistic genius continues to captivate the world.`);

// Guest who can't make it
let guestUnableToAttend: string = guestList[1];
console.log(`\nUnfortunately, ${guestUnableToAttend} can't make it to the dinner.\n`);

// Replace the guest who can't make it with a new person
guestList[1] = "Marie Curie";

// Print invitations with the updated guest list
console.log("Dinner Invitations (Second Set):");

console.log(`Dear ${guestList[0]},\n\tYou are invited to dinner. Please join us for a delightful evening.`);
console.log(`Dear ${guestList[1]},\n\tYou are invited to dinner. Your groundbreaking contributions to science are truly remarkable.`);
console.log(`Dear ${guestList[2]},\n\tYou are invited to dinner. Your artistic genius continues to captivate the world.`);

16. // Store people to invite to dinner in an array
let guestList: string[] = ["Albert Einstein", "Ada Lovelace", "Leonardo da Vinci"];

// Print invitations to each person
console.log("Dinner Invitations (First Set):");

console.log(`Dear ${guestList[0]},\n\tYou are invited to dinner. Please join us for a delightful evening.`);
console.log(`Dear ${guestList[1]},\n\tYou are invited to dinner. Your pioneering work has inspired many.`);
console.log(`Dear ${guestList[2]},\n\tYou are invited to dinner. Your artistic genius continues to captivate the world.`);

// Guest who can't make it
let guestUnableToAttend: string = guestList[1];
console.log(`\nUnfortunately, ${guestUnableToAttend} can't make it to the dinner.\n`);

// Replace the guest who can't make it with a new person
guestList[1] = "Marie Curie";

// Print invitations with the updated guest list
console.log("Dinner Invitations (Second Set):");

console.log(`Dear ${guestList[0]},\n

17. // Store people to invite to dinner in an array
let guestList: string[] = ["Albert Einstein", "Ada Lovelace", "Leonardo da Vinci", "Galileo Galilei", "Nikola Tesla", "Marie Curie", "Marie Antoinette"];

// Print invitations to each person
console.log("Dinner Invitations (First Set):");

for (let guest of guestList) {
    console.log(`Dear ${guest},\n\tYou are invited to dinner. We look forward to having a wonderful time together.`);
}

// Inform about the limited space
console.log("\nUnfortunately, the new dinner table won't arrive in time, and we can only invite two people for dinner.\n");

// Remove guests until only two names remain
while (guestList.length > 2) {
    let removedGuest = guestList.pop();
    console.log(`Sorry, ${removedGuest}, but we can't invite you to dinner.`);
}

// Print invitations to the two remaining people
console.log("\nDinner Invitations (Final Set):");

for (let guest of guestList) {
    console.log(`Dear ${guest},\n\tYou are still invited to dinner. We appreciate your understanding.`);
}

// Remove the last two names to have an empty list
guestList.pop();
guestList.pop();

// Print the empty list
console.log("\nGuest List is Empty:", guestList);

18 . // Store places to visit in an array (not in alphabetical order)
let placesToVisit: string[] = ["Tokyo", "Paris", "New York", "Machu Picchu", "Sydney"];

// Print the array in its original order
console.log("Original Order:", placesToVisit);

// Print the array in alphabetical order without modifying the actual list
console.log("Alphabetical Order:", [...placesToVisit.slice().sort()]);

// Show that the array is still in its original order
console.log("Original Order (Still):", placesToVisit);

// Print the array in reverse alphabetical order without changing the order of the original list
console.log("Reverse Alphabetical Order:", [...placesToVisit.slice().sort().reverse()]);

// Show that the array is still in its original order
console.log("Original Order (Still):", placesToVisit);

// Reverse the order of the list
placesToVisit.reverse();
console.log("Reversed Order:", placesToVisit);

// Reverse the order of the list again
placesToVisit.reverse();
console.log("Back to Original Order:", placesToVisit);

// Sort the array in alphabetical order
placesToVisit.sort();
console.log("Sorted Alphabetical Order:", placesToVisit);

// Sort the array in reverse alphabetical order
placesToVisit.sort((a, b) => b.localeCompare(a));
console.log("Sorted Reverse Alphabetical Order:", placesToVisit);

19. // Store people to invite to dinner in an array
let guestList: string[] = ["Albert Einstein", "Ada Lovelace", "Leonardo da Vinci", "Galileo Galilei", "Nikola Tesla", "Marie Curie", "Marie Antoinette"];

// Print invitations to each person
console.log("Dinner Invitations (First Set):");

for (let guest of guestList) {
    console.log(`Dear ${guest},\n\tYou are invited to dinner. We look forward to having a wonderful time together.`);
}

// Inform about the limited space
console.log("\nUnfortunately, the new dinner table won't arrive in time, and we can only invite two people for dinner.\n");

// Remove guests until only two names remain
while (guestList.length > 2) {
    let removedGuest = guestList.pop();
    console.log(`Sorry, ${removedGuest}, but we can't invite you to dinner.`);
}

// Print the number of people invited to dinner
console.log(`\nNumber of People Invited to Dinner: ${guestList.length}`);

20. // Store a list of favorite books in an array
let favoriteBooks: string[] = ["To Kill a Mockingbird", "1984", "The Great Gatsby", "The Catcher in the Rye", "Pride and Prejudice"];

// Print each book in the array
console.log("Favorite Books:");

for (let book of favoriteBooks) {
    console.log("- " + book);
}

21. // Store information about favorite books in an array of objects
let favoriteBooks: { title: string; author: string; year: number }[] = [
    { title: "To Kill a Mockingbird", author: "Harper Lee", year: 1960 },
    { title: "1984", author: "George Orwell", year: 1949 },
    { title: "The Great Gatsby", author: "F. Scott Fitzgerald", year: 1925 },
    { title: "The Catcher in the Rye", author: "J.D. Salinger", year: 1951 },
    { title: "Pride and Prejudice", author: "Jane Austen", year: 1813 }
];

// Print information about each book
console.log("Favorite Books:");

for (let book of favoriteBooks) {
    console.log(`Title: ${book.title}, Author: ${book.author}, Year: ${book.year}`);
}

22. // Array with three elements
let colors: string[] = ["Red", "Green", "Blue"];

// Intentional error: Access an index that is out of bounds
console.log(colors[3]); // This line will cause an error

// Correct the error: Access a valid index
console.log(colors[2]); // Correct index access

// The program continues...

23. let car = 'subaru';
let number = 42;
let fruit = 'apple';
let isSunny = true;

// Test 1
console.log("Is car == 'subaru'? I predict True.");
console.log(car == 'subaru');

// Test 2
console.log("Is number > 30? I predict True.");
console.log(number > 30);

// Test 3
console.log("Is fruit == 'banana'? I predict False.");
console.log(fruit == 'banana');

// Test 4
console.log("Is car === 'Subaru'? I predict False.");
console.log(car === 'Subaru');

// Test 5
console.log("Is number < 20? I predict False.");
console.log(number < 20);

// Test 6
console.log("Is fruit !== 'apple'? I predict False.");
console.log(fruit !== 'apple');

// Test 7
console.log("Is car != 'honda'? I predict True.");
console.log(car != 'honda');

// Test 8
console.log("Is number >= 42? I predict True.");
console.log(number >= 42);

// Test 9
console.log("Is fruit === 'Apple'? I predict False.");
console.log(fruit === 'Apple');

// Test 10
console.log("Is it sunny? I predict True.");
console.log(isSunny);

24. let string1 = 'apple';
let string2 = 'orange';
let number1 = 25;
let number2 = 40;
let array = [1, 2, 3, 4, 5];

// Tests for equality and inequality with strings
console.log("Test 1: Is string1 == 'apple'? I predict True.");
console.log(string1 == 'apple');

console.log("Test 2: Is string1 != string2? I predict True.");
console.log(string1 != string2);

// Tests using the lower case function
console.log("Test 3: Is string1.toLowerCase() == 'APPLE'? I predict True.");
console.log(string1.toLowerCase() == 'apple');

// Numerical tests
console.log("Test 4: Is number1 > number2? I predict False.");
console.log(number1 > number2);

console.log("Test 5: Is number1 <= number2? I predict True.");
console.log(number1 <= number2);

// Tests using "and" and "or" operators
console.log("Test 6: Is number1 > 20 and number2 < 50? I predict True.");
console.log(number1 > 20 && number2 < 50);

console.log("Test 7: Is number1 > 30 or number2 > 50? I predict False.");
console.log(number1 > 30 || number2 > 50);

// Test whether an item is in an array
console.log("Test 8: Is 3 in the array? I predict True.");
console.log(array.includes(3));

// Test whether an item is not in an array
console.log("Test 9: Is 6 not in the array? I predict True.");
console.log(!array.includes(6));

25. let alienColor: string = 'green';

// If statement to test whether the alien's color is green
if (alienColor === 'green') {
    console.log("Congratulations! You just earned 5 points.");
}
n this version, the alienColor is set to 'green', and the if statement checks if the color is 'green'. Since the condition is true, the message is printed, and the player earns 5 points.

Version 2 (Fails the if test):
let alienColor: string = 'red';

// If statement to test whether the alien's color is green
if (alienColor === 'green') {
    console.log("Congratulations! You just earned 5 points.");
}

26. let alienColor: string = 'green';

// If-else chain to determine points based on the alien's color
if (alienColor === 'green') {
    console.log("Congratulations! You just earned 5 points for shooting the green alien.");
} else {
    console.log("Nice shot! You just earned 10 points for shooting an alien of a different color.");
}

27. Version 1 (Green alien):
 let alienColor: string = 'green';

// If-else chain to determine points based on the alien's color
if (alienColor === 'green') {
    console.log("Congratulations! You just earned 5 points.");
} else if (alienColor === 'yellow') {
    console.log("Congratulations! You just earned 10 points.");
} else if (alienColor === 'red') {
    console.log("Congratulations! You just earned 15 points.");
}
Version 2 (Yellow alien):
let alienColor: string = 'yellow';

// If-else chain to determine points based on the alien's color
if (alienColor === 'green') {
    console.log("Congratulations! You just earned 5 points.");
} else if (alienColor === 'yellow') {
    console.log("Congratulations! You just earned 10 points.");
} else if (alienColor === 'red') {
    console.log("Congratulations! You just earned 15 points.");
}
Version 3 (Red alien):
let alienColor: string = 'red';

// If-else chain to determine points based on the alien's color
if (alienColor === 'green') {
    console.log("Congratulations! You just earned 5 points.");
} else if (alienColor === 'yellow') {
    console.log("Congratulations! You just earned 10 points.");
} else if (alienColor === 'red') {
    console.log("Congratulations! You just earned 15 points.");
}

28. let age: number = 25;

// If-else chain to determine the person's stage of life
if (age < 2) {
    console.log("The person is a baby.");
} else if (age >= 2 && age < 4) {
    console.log("The person is a toddler.");
} else if (age >= 4 && age < 13) {
    console.log("The person is a kid.");
} else if (age >= 13 && age < 20) {
    console.log("The person is a teenager.");
} else if (age >= 20 && age < 65) {
    console.log("The person is an adult.");
} else {
    console.log("The person is an elder.");
}

29. // Array of favorite fruits
let favoriteFruits: string[] = ["banana", "apple", "strawberry"];

// Check for specific fruits in the array
if (favoriteFruits.includes("banana")) {
    console.log("You really like bananas!");
}

if (favoriteFruits.includes("apple")) {
    console.log("You really like apples!");
}

if (favoriteFruits.includes("strawberry")) {
    console.log("You really like strawberries!");
}

if (favoriteFruits.includes("orange")) {
    console.log("You really like oranges!");
} else {
    console.log("Oranges are not in your list of favorite fruits.");
}

if (favoriteFruits.includes("grape")) {
    console.log("You really like grapes!");
} else {
    console.log("Grapes are not in your list of favorite fruits.");
}


30. // Array of usernames
let usernames: string[] = ["admin", "Eric", "Alice", "Bob", "John"];

// Loop through the array and print greetings
for (let username of usernames) {
    // Check if the username is 'admin'
    if (username === "admin") {
        console.log("Hello admin, would you like to see a status report?");
    } else {
        console.log(`Hello ${username}, thank you for logging in again.`);
    }
}

31. // Array of usernames
let usernames: string[] = []; // Empty array

// Check if the list of users is not empty
if (usernames.length > 0) {
    // Loop through the array and print greetings
    for (let username of usernames) {
        // Check if the username is 'admin'
        if (username === "admin") {
            console.log("Hello admin, would you like to see a status report?");
        } else {
            console.log(`Hello ${username}, thank you for logging in again.`);
        }
    }
} else {
    console.log("We need to find some users!");
}

32. // List of current usernames
let currentUsers: string[] = ["Alice", "Bob", "John", "Eve", "Charlie"];

// List of new usernames
let newUsers: string[] = ["Charlie", "David", "Alice", "Frank", "Grace"];

// Loop through new users to check uniqueness
for (let newUser of newUsers) {
    // Check if the new username already exists (case-insensitive)
    let isUsernameTaken = currentUsers.some(
        (currentUsername) => currentUsername.toLowerCase() === newUser.toLowerCase()
    );

    // Print message based on uniqueness
    if (isUsernameTaken) {
        console.log(`Sorry, the username "${newUser}" is already taken. Please choose a new one.`);
    } else {
        console.log(`Congratulations! The username "${newUser}" is available.`);
    }
}


33 . // Ordinal Numbers
let numbers: number[] = [1, 2, 3, 4, 5, 6, 7, 8, 9];

console.log("Ordinal Numbers:");
for (let number of numbers) {
    let ordinalEnding: string;

    if (number === 1) {
        ordinalEnding = "st";
    } else if (number === 2) {
        ordinalEnding = "nd";
    } else if (number === 3) {
        ordinalEnding = "rd";
    } else {
        ordinalEnding = "th";
    }

    console.log(`${number}${ordinalEnding}`);
}

// Pizzas
let favoritePizzas: string[] = ["Pepperoni", "Margherita", "BBQ Chicken"];

console.log("\nMy Favorite Pizzas:");
for (let pizza of favoritePizzas) {
    console.log(`I like ${pizza} pizza.`);
}

console.log("\nI really love pizza!");

34. // Pizzas
let favoritePizzas: string[] = ["Pepperoni", "Margherita", "BBQ Chicken"];

console.log("My Favorite Pizzas:");
for (let pizza of favoritePizzas) {
    console.log(`I like ${pizza} pizza.`);
}

console.log("\nI really love pizza!");

35. // Animals with a common characteristic
let animals: string[] = ["Dog", "Cat", "Rabbit"];

console.log("Common Characteristic: Animals that make great pets\n");

console.log("Names of Animals:");
for (let animal of animals) {
    console.log(animal);
}

console.log("\nStatements about Each Animal:");
for (let animal of animals) {
    console.log(`A ${animal.toLowerCase()} would make a great pet.`);
}

console.log("\nWhat These Animals Have in Common:");
console.log("Any of these animals would make a great pet!");

36. function make_shirt(size: string, message: string): void {
    console.log(`T-Shirt Summary: Size ${size.toUpperCase()}, Message: "${message}"`);
}

// Calling the function with example values
make_shirt("medium", "Hello World!");


37. function make_shirt(size: string = "large", message: string = "I love TypeScript"): void {
    console.log(`T-Shirt Summary: Size ${size.toUpperCase()}, Message: "${message}"`);
}

// Examples of calling the function
make_shirt(); // Large shirt with the default message
make_shirt("medium"); // Medium shirt with the default message
make_shirt("small", "Hello GPT!"); // Small shirt with a custom message

38. function describe_city(city: string, country: string = "default country"): void {
    console.log(`${city} is in ${country}.`);
}

// Calling the function for three different cities
describe_city("Karachi", "Pakistan");
describe_city("Paris", "France");
describe_city("New York"); // Defaults to "default country"

39. function city_country(city: string, country: string): string {
    return `${city}, ${country}`;
}

// Calling the function with three city-country pairs
let result1: string = city_country("Lahore", "Pakistan");
let result2: string = city_country("Paris", "France");
let result3: string = city_country("New York", "USA");

// Printing the values returned
console.log(result1);
console.log(result2);
console.log(result3);

40. function make_album(artist: string, title: string, tracks?: number): { artist: string, title: string, tracks?: number } {
    let album: { artist: string, title: string, tracks?: number } = {
        artist: artist,
        title: title
    };

    if (tracks !== undefined) {
        album.tracks = tracks;
    }

    return album;
}

// Making three dictionaries representing different albums
let album1 = make_album("Artist1", "Album1");
let album2 = make_album("Artist2", "Album2", 12);
let album3 = make_album("Artist3", "Album3", 8);

// Printing each return value
console.log(album1);
console.log(album2);
console.log(album3);

41. function show_magicians(magicians: string[]): void {
    for (let magician of magicians) {
        console.log(magician);
    }
}

// Array of magician's names
let magicianNames: string[] = ["David Copperfield", "Houdini", "Derren Brown", "Penn & Teller"];

// Calling the function to show magicians
show_magicians(magicianNames);

42. function show_magicians(magicians: string[]): void {
    for (let magician of magicians) {
        console.log(magician);
    }
}

function make_great(magicians: string[]): string[] {
    // Create a new array with the modified names
    let greatMagicians: string[] = [];

    for (let magician of magicians) {
        greatMagicians.push(`the Great ${magician}`);
    }

    return greatMagicians;
}

// Array of magician's names
let magicianNames: string[] = ["David Copperfield", "Houdini", "Derren Brown", "Penn & Teller"];

// Calling make_great to modify the array
let greatMagicians = make_great(magicianNames);

// Calling show_magicians to see the modified list
show_magicians(greatMagicians);

43. function show_magicians(magicians: string[]): void {
    for (let magician of magicians) {
        console.log(magician);
    }
}

function make_great(magicians: string[]): string[] {
    // Create a new array with the modified names
    let greatMagicians: string[] = [];

    for (let magician of magicians) {
        greatMagicians.push(`the Great ${magician}`);
    }

    return greatMagicians;
}

// Array of magician's names
let magicianNames: string[] = ["David Copperfield", "Houdini", "Derren Brown", "Penn & Teller"];

// Call make_great with a copy of the original array
let greatMagicians = make_great([...magicianNames]); // Using the spread operator to create a copy

// Calling show_magicians to show the original array
console.log("Original Magicians:");
show_magicians(magicianNames);

// Calling show_magicians to show the modified array
console.log("\nGreat Magicians:");
show_magicians(greatMagicians);

44. function make_sandwich(...items: string[]): void {
    console.log("Sandwich Summary:");
    if (items.length === 0) {
        console.log("No items. It's a plain sandwich.");
    } else {
        console.log("Items: " + items.join(", "));
    }
    console.log("\n");
}

// Calling the function with different numbers of arguments
make_sandwich("Ham", "Cheese", "Lettuce");
make_sandwich("Turkey", "Swiss");
make_sandwich(); // No items, plain sandwich

45. function create_car(manufacturer: string, model: string, ...options: { [key: string]: any }[]): { manufacturer: string, model: string, [key: string]: any } {
    let car: { manufacturer: string, model: string, [key: string]: any } = {
        manufacturer: manufacturer,
        model: model
    };

    // Adding optional key-value pairs to the car object
    for (let option of options) {
        for (let key in option) {
            car[key] = option[key];
        }
    }

    return car;
}

// Calling the function with required and optional information
let carInfo = create_car("Toyota", "Camry", color: "Blue", features: ["GPS", "Sunroof"]);

// Printing the returned object
console.log(carInfo);











