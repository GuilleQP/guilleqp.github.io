<audio controls>
  <source src="a.mp3" type="audio/mp3">
  <p>Your browser doesn't support MP3 audio.</p>
</audio>

<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script> 

<div class="progress">
  <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="50"
  aria-valuemin="0" aria-valuemax="100" style="width:3%">
    3% Complete
  </div>
</div>

<script src="https://unpkg.com/mermaid@8.1.0/dist/mermaid.min.js"></script>

<div class="mermaid">
classDiagram
Romans --> Units
Romans --> Structures
Units --> Builder
Units --> Legionary
Units --> Archer
Units --> Centurion
Structures --> TownCenter
Structures --> Fountain
Structures --> Barracks
Structures --> TrainingField
Structures --> FortifiedCamp
Structures --> WheatField
Structures --> House
Builder o-- Fountain
Builder o-- Barracks
Builder o-- TrainingField
Centurion o-- FortifiedCamp
Builder o-- WheatField
TownCenter *-- Builder
TownCenter *-- Centurion
Barracks *-- Legionary
Barracks *-- Archer
Legionary : Close combat
Legionary : HP = 110
Legionary : DPS = 15
Archer : Distance
Archer : HP = 80
Archer : DPS = 10
Builder : Long training time
Builder : HP = 100
Builder : DPS = 0
Centurion : Close combat
Centurion : Damage bonus to nearby units
Centurion : HP = 200
Centurion : DPS = 20
TownCenter : Central faction structure
Fountain : Heal nearby units
Barracks : Train attack units
TrainingField : Level up units
WheatField : Produces food
FortifiedCamp : Defense bonus
House : Increase population limit
</div>

## Projects ⚙
### **Daily reading list** 📰
List with interesting resources and news about computer science, artificial intelligence, economics, politics... The best way to start your day with a morning reading session. [Go to list](projects/daily_read.md)