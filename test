var playGame = function () {

var userChoice = prompt("Do you choose rock, paper, scissors, or rope?");
var computerChoice = Math.random();

console.log("computer chooses: " + computerChoice);

if (computerChoice <= 0.25) {
    computerChoice = "rock";
} else if (computerChoice <= 0.50) {
    computerChoice = "paper";
} else if (computerChoice <= 0.75) {
    computerChoice = "scissors";
} else {
    computerChoice = "rope";
}

console.log("computer chooses: " + computerChoice);
console.log("user chooses: " + userChoice);

var compare = function (choice1,choice2) {
    if ( choice1 === choice2 ) {
        return "tie";
    }
    else if ( choice1 === "rope" ) {
        return "rope wins";
    }
    else if ( choice2 === "rope" ) {
        return "rope wins";
    }
    else if ( choice1 === "rock" ) {
        if ( choice2 === "scissors" ) {
            return "rock wins";
        } else {
            return "paper wins";
        }
    }
    else if ( choice1 === "paper" ) {
        if ( choice2 === "rock" ) {
            return "paper wins";
        } else {
            return "scissors wins";
        }
    }
    else if ( choice1 === "scissors" ) {
        if ( choice2 === "rock" ) {
            return "rock wins";
        } else {
            return "scissors wins";
        }
    }   
    else {
        return "inappropriate choice ";
    }

    if (tie === 1) {
        alert("It's a tie!");
        playGame();
    }

};

var result = compare(userChoice, computerChoice);
if (result === "tie") {
    alert("it's a tie!");
    playGame();
} else {
    console.log(result);
}

};

playGame();