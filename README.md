# JavaScript-guessing-game
JavaScript Guessing Games
 <script>
        //guessing game
        //guess A number from 1 to 5
        //generate arandom number 1to 5
        //if the guess number matches random number
        //run the game for 5 time
        //show the number of won and lost
        var guessNumber=parseInt(prompt("Enter a number from 1 to 5:"));
      var randomNumber= Math.floor(Math.random())*5 +1;
     if(guessNumber==randomNumber){
 console.log("You have won");
     }else{
       console.log("You have lost: Random number was" +randomNumber);
     }
     </script>
     //another
      var numberOfWon=0;
        var NumberOfLost=0;
        for(var i=1; i<=5; i++){
          var guessNumber=parseInt(prompt("Enter a number from 1 to 5:"));
      var randomNumber= Math.floor(Math.random())*5 +1;
     if(guessNumber==randomNumber){
  document.write("You have won");
   numberOfWon++;
     }else{
       document.write("You have lost: Random number was" +randomNumber);
    numberOfLost++;
      }
        }
       document/write("Total number of won=" +numberOfWon+ "<br>");
       document/write("Total number of won=" +numberOfLost+ "<br>");
    </script>
