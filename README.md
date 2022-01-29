# Assignment-for-JavaScript---Floxus

1)The table with id="age-table". 
-> table = document.getElementById("age-table")

2) All label elements inside that table (there should be 3 of them).
-> label = document.getElementById("age-table").querySelectorAll("label")

3) The first td in that table (with the word “Age”). 
-> td = document.getElementById("age-table").querySelector("td")

4) The form with name="search". 
-> form = document.querySelector("form")

5) The first input in that form. The last input in that form.
-> firstInput = document.querySelector("form").querySelectorAll("input")
 for first input
 firstInput[0]
 
 for last input 
 firstInput[firstInput.length-1]
