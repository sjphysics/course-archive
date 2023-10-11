  <button class="btn js-toggle-dark-mode">Dark Mode</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Dark Mode';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to light mode';
  }
});
</script>

# Mid Exam Stats
This page contains analyses for the 2nd Quarter Mid Exam. 
## Individual Grade Viewer
[Launch Grade Viewer](/viewer/start)
# Midterm 1 Tendecies:
## 10 A
The average score out of 20, was **9.677777777777777**  with the standard deviation being **6.068274105318904**
#### 10 A Grade Distribution
![histogram](/viewer/start/analysis/2ndMid/10A.png)
## 10 B
The average score out of 20, was **10.423076923076923**  with the standard deviation being **4.650666428035026**
#### 10 B Grade Distribution
![histogram](/viewer/start/analysis/2ndMid/10B.png)
## 10 C
The average score out of 20, was **9.879310344827585**  with the standard deviation being **5.157276701191396**
#### 10 C Grade Distribution
![histogram](/viewer/start/analysis/2ndMid/10C.png)
## 10 D
The average score out of 20, was **8.476190476190476**  with the standard deviation being **5.782725075347448**
#### 10 D Grade Distribution
![histogram](/viewer/start/analysis/2ndMid/10D.png)
## 10 E
The average score out of 20, was **9.544642857142858**  with the standard deviation being **4.490343593394017**
#### 10 E Grade Distribution
![histogram](/viewer/start/analysis/2ndMid/10E.png)
