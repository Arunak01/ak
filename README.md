# ak
<!DOCTYPE html>
<html>
<head>
    <title>identify symptoms of Corona</title>
   </head>
   <body bgcolor="aqua">
  
<div id="menu-1">
    <h3>Covid-19 Self Detector</h3>
    <p>If you want to detect, whether you were infected by covid-19 or not, you are at the right place. Just answer the questions and find whether you are safe.</p >
   <span id="image"> <img src=" https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTwOnOP91nfngCD_tdJVVoL5K-YWBGON3f7Uf5hvq6cQcHWAIa5&usqp=CAU " width="400px" height="400px" style:"border-color="green",border="5"> </image>
    <p>Lets break the chain by being seperated and virtually connected </p>
    <input type="button" name="" value="Click here to start" id="start" align="center" onclick="one()" class="button">
     </br>
</div>
<div id="menu-2" >
    <form name="quiz">
    <div class="question">
        <p>1. Do you have headache?</p >
    <input type="radio" name="question1" value="Yes" class="button">Yes
    <input type="radio" name="question1" value="No" class="button">No
    </div>

    <div class="question" >
    <p>2. Do you have fever which is higher than 37.5 degree?</p >
    <input type="radio" name="question2" value="Yes" class="button">Yes
    <input type="radio" name="question2" value="No" class="button">No
    </div>

    <div class="question"  >
    <p>3. Did you find it hard to breath?</p >
    <input type="radio" name="question3" value="Yes" class="button">Yes
    <input type="radio" name="question3" value="No" class="button">No
    </div> 

    <div class="question"  >
    <p>4. Are you often feeling tired even if you do nothing?</p >
    <input type="radio" name="question4" value="Yes" class="button">Yes
    <input type="radio" name="question4" value="No" class="button">No
    </div>

    <div class="question" >
    <p>5. Are you feeling some muscle pains?</p >
    <input type="radio" name="question5" value="Yes" class="button">Yes
    <input type="radio" name="question5" value="No" class="button">No
    </div>

    <div class="question"  >
    <p>6. Do you cough?</p >
    <input type="radio" name="question6" value="Yes" class="button">Yes
    <input type="radio" name="question6" value="No" class="button">No
    </div>
  <div class="question">
    <p>7. Do you have sore throat?</p >
    <input type="radio" name="question7" value="Yes" class="button">Yes
    <input type="radio" name="question7" value="No" class="button">No
    </div>
       <div class="question">
    <p>8. Do you smoke?</p >
    <input type="radio" name="question8" value="Yes" class="button">Yes
    <input type="radio" name="question8" value="No" class="button">No
    </div>
       <div class="question">
    <p>9. Are you a foreign return?</p >
    <input type="radio" name="question9" value="Yes" class="button">Yes
    <input type="radio" name="question9" value="No" class="button">No
    </div>
      <div class="question">
    <p>10. Some patients experience loss of taste or smell.Do you experience any?</p >
    <input type="radio" name="question10" value="Yes" class="button">Yes
    <input type="radio" name="question10" value="No" class="button">No
    </div>
        <div class="question">
    <p>11. Age is also a risk for corona-virus.Are you above 60?</p >
    <input type="radio" name="question11" value="Yes" class="button">Yes
      <input type="radio" name="question11" value="No" class="button">No
    </div> 
       
       </br>
    <input type="button" name="" value="Submit the answers" onclick="check()" class="button">
    
    </form>
    
</div>
 <div id="menu-3">
<p id="text">
</p>
 </br> 
    <input type="button" name="" value="Awareness tips"  onclick="aware()" class="button"> 
  
 </div>

<script type="text/javascript">
    
    function one() {
    var menu1=document.getElementById('menu-1');
    var menu2=document.getElementById("menu-2");
    menu1.style.display="none";
    menu2.style.display="block"
};
function check() {
    var c=0;
  var question1=document.quiz.question1.value;
  var 
