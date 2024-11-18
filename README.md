# task-2
personal portfolio
Portfolio Structure

1. Index.html: Homepage with introduction, skills, and projects.
2. Projects.html: Detailed project descriptions with images.
3. Resume.html: Your resume.
4. Styles.css: CSS styling.
5. Script.js: JavaScript interactivity.

HTML (Index.html)


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
            </ul>
        </nav>
    </header>
    <section id="intro">
        <h1>Your Name</h1>
        <p>Web Developer/Java Developer</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <h3>Online Quiz Platform</h3>
                <p>Brief description</p>
            </li>
            <li>
                <h3>Simple Banking Application</h3>
                <p>Brief description</p>
            </li>
        </ul>
    </section>
    <section id="resume">
        <h2>Resume</h2>
        <embed src="resume.pdf" type="application/pdf">
    </section>
    <script src="script.js"></script>
</body>
</html>


CSS (Styles.css)


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline-block;
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2em;
}

h1, h2, h3 {
    color: #333;
}

#intro {
    background-color: #f7f7f7;
}


JavaScript (Script.js)


// Add interactivity, e.g., scrolling effects, modal windows


Simple Banking Application (Java)

Create a new Java project with the following files:

BankingApp.java


import java.util.Scanner;

public class BankingApp {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double balance = 0;

        while (true) {
            System.out.println("1. Deposit");
            System.out.println("2. Withdraw");
            System.out.println("3. Check Balance");
            System.out.println("4. Exit");
            System.out.print("Choose an option: ");
            int option = scanner.nextInt();

            switch (option) {
                case 1:
                    System.out.print("Enter amount to deposit: ");
                    double deposit = scanner.nextDouble();
                    balance += deposit;
                    System.out.println("Deposit successful!");
                    break;
                case 2:
                    System.out.print("Enter amount to withdraw: ");
                    double withdraw = scanner.nextDouble();
                    if (balance >= withdraw) {
                        balance -= withdraw;
                        System.out.println("Withdrawal successful!");
                    } else {
                        System.out.println("Insufficient balance!");
                    }
                    break;
                case 3:
                    System.out.println("Balance: " + balance);
                    break;
                case 4:
                    System.out.println("Exiting...");
                    return;
                default:
                    System.out.println("Invalid option!");
            }
        }
    }
}


GitHub Repository

1. Create a new repository on GitHub.
2. Initialize a local Git repository: git init.
3. Add files: git add ..
4. Commit changes: git commit -m "Initial commit".
5. Link local repository to GitHub: git remote add origin <repository_url>.
6. Push changes: git push -u origin master.
7. Share your portfolio link!

Online Quiz Platform

Create a new HTML file (quiz.html) and add the following code:


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz</title>
    <script>
        // Quiz logic
        let questions = [
            { question:

Here's a step-by-step guide to creating a personal portfolio and hosting it on GitHub:

Portfolio Structure

1. Index.html: Homepage with introduction, skills, and projects.
2. Projects.html: Detailed project descriptions with images.
3. Resume.html: Your resume.
4. Styles.css: CSS styling.
5. Script.js: JavaScript interactivity.

HTML (Index.html)


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
            </ul>
        </nav>
    </header>
    <section id="intro">
        <h1>Your Name</h1>
        <p>Web Developer/Java Developer</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <h3>Online Quiz Platform</h3>
                <p>Brief description</p>
            </li>
            <li>
                <h3>Simple Banking Application</h3>
                <p>Brief description</p>
            </li>
        </ul>
    </section>
    <section id="resume">
        <h2>Resume</h2>
        <embed src="resume.pdf" type="application/pdf">
    </section>
    <script src="script.js"></script>
</body>
</html>


CSS (Styles.css)


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline-block;
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2em;
}

h1, h2, h3 {
    color: #333;
}

#intro {
    background-color: #f7f7f7;
}


JavaScript (Script.js)


// Add interactivity, e.g., scrolling effects, modal windows


Simple Banking Application (Java)

Create a new Java project with the following files:

BankingApp.java


import java.util.Scanner;

public class BankingApp {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double balance = 0;

        while (true) {
            System.out.println("1. Deposit");
            System.out.println("2. Withdraw");
            System.out.println("3. Check Balance");
            System.out.println("4. Exit");
            System.out.print("Choose an option: ");
            int option = scanner.nextInt();

            switch (option) {
                case 1:
                    System.out.print("Enter amount to deposit: ");
                    double deposit = scanner.nextDouble();
                    balance += deposit;
                    System.out.println("Deposit successful!");
                    break;
                case 2:
                    System.out.print("Enter amount to withdraw: ");
                    double withdraw = scanner.nextDouble();
                    if (balance >= withdraw) {
                        balance -= withdraw;
                        System.out.println("Withdrawal successful!");
                    } else {
                        System.out.println("Insufficient balance!");
                    }
                    break;
                case 3:
                    System.out.println("Balance: " + balance);
                    break;
                case 4:
                    System.out.println("Exiting...");
                    return;
                default:
                    System.out.println("Invalid option!");
            }
        }
    }
}


