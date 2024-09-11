class Student {
    // Data (Properties)
    constructor(name, age, standard) {
        this.Name = name;
        this.Age = age;
        this.Standard = standard;
    }

    // Methods (Actions)
    study() {
        // Study
    }

    play() {
        // Play
    }

    doHomeWork() {
        // Do Homework
    }
}

// Create an instance of the Student class
const student = new Student('Jayson', 20, '10th');

// Console the Name property
console.log(student.Name); // Output: Jayson


///////////////////////////////////////////

class Student {
    // Constructor to initialize properties
    constructor(name, age, standard) {
        this.Name = name;
        this.Age = age;
        this.Standard = standard;
    }

    // Method to simulate studying
    study() {
        console.log(`${this.Name} is studying.`);
    }

    // Method to simulate playing
    play() {
        console.log(`${this.Name} is playing.`);
    }

    // Method to simulate doing homework
    doHomeWork() {
        console.log(`${this.Name} is doing homework.`);
    }
}

// Create an instance of the Student class
const student = new Student('Jayson', 20, '10th');

// Call the methods and observe the output
student.study();      // Output: Jayson is studying.
student.play();       // Output: Jayson is playing.
student.doHomeWork(); // Output: Jayson is doing homework.

this keyword refers to the object that is currently executing or calling the function

git config --global user.name "Your Name"
git config --global user.email "Your EMail address"
