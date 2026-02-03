# Math Game in C++

This repository contains **two C++ implementations** of a **Math Quiz Game**.  
Both files allow the player to answer arithmetic questions with different levels of difficulty and operator types.  
This project was developed for the course **Algorithms & Problem-Solving – Level 2** with Dr. Abu Hadhoud.

## Overview of the Two Files

### File 1
- Uses **enums** for question levels (`Easy`, `Midum`, `Hard`, `MixLevel`) and operator types (`Sum`, `Sub`, `Mult`, `Div`, `MixOperator`).  
- Uses a single struct `stInfoGame` to store game information such as number of questions, number of correct/incorrect answers, level, and operator type.  
- Functions generate numbers based on the chosen level and operator type.  
- Checks each answer, updates counters, and changes screen color according to correctness.  
- Displays final results with emojis indicating pass, fail, or draw.

### File 2
- Uses **enums** for question levels (`EasyLevel`, `MedLevel`, `HardLevel`, `Mix`) and operator types (`Add`, `Sub`, `Mult`, `Div`, `MixOp`).  
- Uses two structs: `stQuestion` for each question and `stQuizz` for the whole quiz.  
- Functions are more modular: generating questions, reading player input, checking correctness, and printing results.  
- Keeps a list of all questions, their correct answers, and player answers.  
- Shows correct answers immediately if the player was wrong and updates screen color.  
- Determines pass/fail based on the number of correct vs wrong answers.

## Key Differences Between the Two Files

| Feature                   | File 1                  | File 2                              |
|---------------------------|-----------------------|------------------------------------|
| Data Organization         | Single struct `stInfoGame` | Two structs: `stQuestion` + `stQuizz` |
| Functions                 | Fewer, longer functions | Many small, modular functions       |
| Question Generation       | Random numbers based on level | Random numbers and operator type, stored in list |
| Answer Checking           | Updates counters, shows emoji | Shows correct answer if wrong, updates counters |
| Screen Color              | Changes for each answer | Changes for each answer             |
| Extensibility             | Harder to extend        | Easier to extend with structs       |

## How to Run

1. Download the `.cpp` file.  
2. Open it in a C++ IDE (Visual Studio, Code::Blocks, VS Code with C++ compiler, etc.).  
3. Compile and run the program.  
4. Enter the number of questions you want to answer (usually 1-10).  
5. Choose the difficulty level: Easy, Medium, Hard, or Mix.  
6. Choose the operator type: Add, Subtract, Multiply, Divide, or Mix.  
7. Answer each question. The program will immediately show whether your answer is correct and update the screen color.  
8. At the end, the program displays the total results, including number of correct and wrong answers, level, operator type, and pass/fail.

---
<div align="center">

<h2>Majdi Al-Hijazi</h2>
<p>💻 Computer Information Systems (CIS) Student</p>

<br>

<a href="https://github.com/MajdiAl-Hijazi" target="_blank">
  <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="40" />
</a>

<a href="https://www.linkedin.com/in/majdi-alhijazi-274947334" target="_blank">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="40" />
</a>

<a href="mailto:majdialhijazi@gmail.com">
    <img src="https://img.icons8.com/color/48/000000/gmail.png" alt="Email" width="40"/>

</div>

