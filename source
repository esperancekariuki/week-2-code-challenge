document.addEventListener("DOMContentLoaded", () => { 
  const subnitButton = document.querySelector("#submit"); 
  subnitButton.addEventListener("click", formSubmit, false); 
}); 
 
 
 
 
function formSubmit(event) { 
   
  var toDoItem = document.getElementById("new-task-description").value; 
  if(toDoItem === undefined || toDoItem == null || toDoItem.length <= 0){ 
    alert("To do item not provided"); 
  } 
  else{ 
    var ul = document.getElementById("list"); 
    var li = document.createElement("li"); 
    li.appendChild(document.createTextNode(toDoItem)); 
    ul.appendChild(li); 
    document.getElementById("new-task-description").value = ""; 
  } 
   
  event.preventDefault(); 
 
}