# 🌊Resume in Flow chart.
````markdown
Resume of my work past experiences.
````

<p align="center" dir="auto" style="max-width:100%;">
    <img align="center" dir="auto" src="https://img.shields.io/badge/version-2.0-blue" width="85" style= "max-width: 100%;">
    <img align="center" dir="auto" src="https://img.shields.io/badge/license-CC0_1.0-green" width="111" style="max-width: 100%;">
    
</p>

``` mermaid
classDiagram

%%Academic History chart
Academic_History --* Associate_Degree_in
Associate_Degree_in : Systems Analysis and Development[Institution_Multivix] --- Status_Pursuing🏃
Associate_Degree_in : The Odin Project "Foundations Course"[Community Academic Project] --- Status_Pursuing🏃
Associate_Degree_in : System Development [Institution_SENAI] --- Status(Complete)🏆
Associate_Degree_in : Psicologist [Institution_FAVI] --- Status(Complete)🏆

%%Work place chart
Professional_Experience--> WorkP1 : Working Currently
Professional_Experience --> WorkP2: Worked Previously

WorkP1 : Ctrl+Play🚀
WorkP1 : Entry--April/08/2025
WorkP1 : RolePerformed = System internship in systems analysis and development()

WorkP2 : SilkPress📦
WorkP2 : Entry--08/15/2024 Terminated--02/21/2025
WorkP2 : RolePerformed = Storage Manager()

%%IDE Knowledge Chart
IDE Knowledge --> Basic
IDE Knowledge --> Intermediate
IDE Knowledge --> Advanced

class Basic {
    Pycharm🐍
    Arduino IDE🟦
    Google Colab(🐍)
}   
class Intermediate {
   Net Beans(☕)   
   IntelliJ ☕
}
note for Advanced "In Construction..."
class Advanced { 
 
}

%%Style Code
classDef default fill:#E0CB2B,color:red

class Professional_Experience:::mainclass
classDef mainclass color:#3A2BE0


style Associate_Degree_in fill:#92E02B,stroke-width:3px

style WorkP1 fill:#DEE02B,stroke-width:3px
style WorkP2 fill:#DEE02B,stroke-width:3px

style Basic fill:#E0B52B
style Intermediate fill:#E0B52B
style Advanced fill:#E0B52B

style Professional_Experience fill:#E0D475,stroke:#103,stroke-width:6px
style IDEKnowledge fill:#E0D475,stroke:#103,stroke-width:6px
style Academic_History fill:#E0D475,stroke:#103,stroke-width:6px

```
