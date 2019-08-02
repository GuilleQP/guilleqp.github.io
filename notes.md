<audio controls>
  <source src="a.mp3" type="audio/mp3">
  <p>Your browser doesn't support MP3 audio.</p>
</audio>

<script src="https://unpkg.com/mermaid@8.1.0/dist/mermaid.min.js"></script>

<div class="mermaid">
classDiagram
Romans --> Units
Romans --> Structures
Romans : aasd
Units --> Builder
Units --> Legionary
Units --> Archer
Structures --> TownCenter
Structures --> Fountain
Structures --> Barracks
Builder o-- Fountain
Builder o-- Barracks
Builder : asd
TownCenter *-- Builder
Barracks *-- Legionary
Barracks *-- Archer
Legionary : Close combat
Legionary : HP = 100
Legionary : DPS = 10
</div>