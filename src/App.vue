<template>
  <div id="app">
    <a href="https://engineering.virginia.edu/departments/computer-science" target="_blank">
      <img src="/Virginia_Cavaliers_logo.svg.png" alt="UVA Logo" class="uva-logo" />
    </a>
    <div class="dropdown-container">
      <div class="dropdown">
        <button class="dropbtn">Projects</button>
        <div class="dropdown-content">
          <a href="https://github.com/agrimreaper49/Battleship">Battleship</a>
          <a href="https://github.com/agrimreaper49/Course-Compass">Course Compass</a>
          <a href="https://github.com/iliterobotics/FRC-Robot-2022">ILITE Robotics</a>
          <a href="https://github.com/agrimreaper49/ClubMatch">Club Compass</a>
          <a href="https://github.com/agrimreaper49/SudokuApp">Sudoku App</a>
        </div>
      </div>
      <div class="dropdown">
        <button class="dropbtn">Contact</button>
        <div class="dropdown-content">
          <a href="mailto:agrimsharma571@gmail.com">Email</a>
        </div>
      </div>
    </div>

    <footer class="footer">
      asharma | 2023
    </footer>

    <div class="container">
      <h1>Agrim Sharma</h1>
      <p>Computer Science @ UVA. Aspiring Software Engineer.</p>
      <a href="https://github.com/agrimreaper49" target="_blank">
        <i class="fab fa-github social-icon"></i>
      </a>
      <a href="https://www.linkedin.com/in/agrim-sharma571/" target="_blank">
        <i class="fab fa-linkedin social-icon"></i>
      </a>
      <a href="https://drive.google.com/file/d/1rH61pHWKnAjw4cvIqna7Xhgsppw8RMlf/view?usp=sharing" target="_blank">
        <i class="fas fa-file-alt social-icon"></i>
      </a>
    </div>
  </div>
</template>


<style>
.footer {
  text-align: center;
  position: absolute;
  font-family: 'Rubik', sans-serif;
  padding: 20px;
  bottom: 0;
}
.dropdown-container {
  margin-top: 0px;
  display: flex;
  align-items: flex-start;
  justify-content: flex-start;
}
.dropbtn {
  background-color: transparent;
  font-family: 'Rubik', sans-serif;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
  transition: background-color 0.1s;
}
.dropbtn:hover {
  background-color: #d9d9d9;
}

.dropdown:hover .dropbtn {
  background-color: #d9d9d9; 
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown-content {
  font-family: 'Rubik', sans-serif;
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  font-family: 'Rubik', sans-serif;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1;}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown {
 display: inline-block;
  margin-right: 5px;
}
.uva-logo {
  position: absolute;
  top: 10px; 
  right: 20px; 
  height: 40px; 
  width: auto; 
}
.social-icon {
  font-size: 1.5em; 
  margin-right: 10px; 
}

#app {
  text-align: center;
  color: #2c3e50;
}

.container {
  margin-top: 60px;
}

h1 {
  font-family: 'Rubik', sans-serif;
  font-size: 2em;
  margin-bottom: 0;
}

p {
  font-family: 'Rubik', sans-serif;
  font-size: 1.2em;
  color: #34495e;
}
</style>

