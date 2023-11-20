<!DOCTYPE HTML>
   <head lang="en" dir="ltr">
     <meta charset="utf-8">
   <title></title>
</head>
  <body>
    <h4>Registration Form</h4>
    <form action="/action.php">
      <input type="text" placeholder="username">
        <br><br>
          <input type="password" placeholder="password">
            <br><br>
              <h5>Select your class</h5>
             <label for="101">
             <input type="radio" name="class" value="class XI" id="101">Class XI
          </label>
       <br><br>
     <label for="102">
   <input type="radio" name="class" value="class XII" id="102">Class XII
</label>
<h5>Select Fav Subject</h5>
  <label for="math">
   <input type="checkbox" name="subject" value="math" id="101">Math
     </label>
     <br><br>
       <label for="phy">
        <input type="checkbox" name="subject" value="phy" id="102">physic
         </label>
         <br><br>
            <label for="chem">
           <input type="checkbox" name="subject" value="chem" id="103">chemistry
         </label>
         <br><br>
        <label for="CS">
       <input type="checkbox" name="subject" value="CS" id="104">Computer science
     </label>
<br><br>
Select your City
     <select name="City">
       <option value="Dhaka">dhaka</option>
       <option value="Raj">Rajshahi</option>
       <option value="chapai">chapai</option>
       <option value="josor">josor</option>
       <option value="khulna">khulna</option>
     </select>
     <br><br>
     <textarea name="Feedback" id="101" placeholder="Please give your valuable Feedback here" rows="2">
     </textarea>
     <br>
     <input type="Submit" value="Submit">
    </form>
  </body>
</HTML>
