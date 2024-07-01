# to-do-list
/*html*/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>to do list</h1>
    <input type="text" id="taskInput" placeholder="enter your letter" id="imput">
    <button onclick="add()">add</button>
    <ul id="contianer">
    </ul>
    
</body>
</html>
/*css*/
body{
    background-color: aqua;
    color: black;
    align-items: center;
    justify-content: center;
}
.data{
    align-items: center;
    justify-content: center;
    text-align: center;
    background-color:rgb(8, 49, 59);
    color: white;
    margin-top: 2%;
    padding: 8%;
    width: 15rem;
    margin-left: 35%;
    border-radius: 50px;
}
#imput{
    width: 100%;
    height: 100%;
    font-size: 15px;
    padding: 5px;
}
.flex{
    display: flex;
}
.add{
    padding: 5px;
    font-size: 15px;
    margin-left: 10px;
}
.del{
    padding: 5px;
var ul = document.getElementById("place")
var input = document.getElementById("imput")
function add() {
    var list = document.createElement("tr")
    list.innerHTML = imput.value + "<button onclick='comp(event)' class='comp'>complete</button><button onclick='del(event)' class='del'>delete</button>"
    ul.append(list)
}
function del(event) {
    event.target.parentElement.remove()
}
function comp(event) {
    event.target.parentElement.style.backgroundColor="green";
}
    font-size: 15px;
    margin-left: 10px; 
    background-color: red;
    border: none;
    border-radius: 10px;
}
h1{
    font-family:Arial, Helvetica, sans-serif;
    font-size: 45px;
 padding: 2%;
    font-size: 20px;
    margin-left: 10px; 
    margin-top: 3%;
    background-color:rgb(8, 49, 59);
    color: white;
    border: none;
    border-radius: 10px;
    align-items: center;
    justify-content: center;
    text-align: center;
}
.comp{
    padding: 5px;
    font-size: 15px;
    margin-left: 10px; 
    background-color:green;
    border: none;
    border-radius: 10px;
}
tr{
    border: 1px solid black;
    border-collapse: collapse;
    padding: 10px;
    margin-top: 10%;
    }
.comp::after{
    color: white;
    color: black;
}
.floor{
    padding: 5%;
    font-size: 20px;
    margin-left: 10px; 
    margin-top: 3%;
    background-color:rgb(8, 49, 59);
    color: white;
    border: none;
    border-radius: 10px;
    align-items: center;
    justify-content: center;
    text-align: center;

}
/*javascript*/

var ul = document.getElementById("place")
var input = document.getElementById("imput")
function add() {
    var list = document.createElement("tr")
    list.innerHTML = imput.value + "<button onclick='comp(event)' class='comp'>complete</button><button onclick='del(event)' class='del'>delete</button>"
    ul.append(list)
}
function del(event) {
    event.target.parentElement.remove()
}
function comp(event) {
    event.target.parentElement.style.backgroundColor="green";
}
