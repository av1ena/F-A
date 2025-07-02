const questions = [
    "The signs were there all along. You were starting to get burned out and was always trying to carry everything in silence while still trying to love me the best way you could.",
    "I'm sorry I wasn't fully there for you. You shouldn't have to go through it alone, and yet you did because that's just who you are. You don't always have to be strong. Not with me. I would've listened and opened my arms for you.",
      "You said sorry regarding my parents. I kept interrogating you and I regret it. You shut down and now we are both silent. Is this how our story ends?",
  "Can you tell me what was really going through your mind the moment you decided to let me go?" , 
  "Silence for a day and suddenly dropping the bomb. You sounded so sure. Or was it just easier to leave than explain?",
  "Did you truly stop loving me, or are you just overwhelmed? ",
  "Love doesn't vanish like that. It gets buried under fear, silence and ego.",
  "When things get heavy and serious, is shutting down your way of protecting yourself?",
  "Is that what you have always done? Disappear before it hurts? But love isn't supposed to be easy. So why not stay and fight?" , 
  "What would have to change for you to give us another chance?",
  "Are you afraid of being vulnerable sometimes?",
  "Is letting me go your way of showing love?",
  "Then why did you love me so deeply? Why go so far, only to pull away eventually?",
  "Did I even matter or was I just convenient at the time?",
  

];

let currentQuestion = 0;

const startScreen = document.getElementById("start-screen");
const gameScreen = document.getElementById("game-screen");
const endScreen = document.getElementById("end-screen");

const startButton = document.getElementById("start-button");
const cardQuestion = document.getElementById("card-question");
const option1 = document.getElementById("option1");
const option2 = document.getElementById("option2");

startButton.addEventListener("click", () => {
  startScreen.classList.remove("active");
  gameScreen.classList.add("active");
  showQuestion();
});

function showQuestion() {
  if (currentQuestion < questions.length) {
    cardQuestion.textContent = questions[currentQuestion];
  } else {
    gameScreen.classList.remove("active");
    endScreen.classList.add("active");
  }
}

function nextQuestion() {
  currentQuestion++;
  showQuestion();
}

option1.addEventListener("click", nextQuestion);
option2.addEventListener("click", nextQuestion);