# overlapping_area

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#change-log">Change log</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

The project inspiration is to calculate the overlapping area of two layers in L-Edit using a script.  

* The script creates a new layer **booleanAND**
* It then uses the boolean operation AND to creates new objects wherever both layers intersect
* The area of these objects is then calculated and displayed in a dialog.
* The objects and the layer are then removed.

### Built With

* C++
* Tanner L-Edit

<!-- GETTING STARTED -->
## Getting Started

To get started with using this code, ensure you have Tanner tools installed with an open design.

### Prerequisites

The C++ compiler MinGW is bundled with tanner tools so no need to install any compilers

The following header files on top of the default ones added by L-Edit at default  are needed for L-Edit functions to work.

* vector.h
* string.h
* ldata.h

### Installation

1. Open the project at **.insert local path of script here** with an editor. Preferrably [**vscode**](https://code.visualstudio.com/)
2. You could also clone the repo

   ```sh
   git clone https://github.com/EDA-Solutions-Limited/overlapping_area.git

<!-- MAKING CHANGES -->
## Usage

* Drag and drop the UPI macro into L-Edit and go to Tools -> Execute Script or simply the F5 hotkey
* Alternatively, you could go to Tools -> Macro -> Load, navigate to the path of the script. Click on Run
* Ensure you have made a selection in the design for the objects you intend to grown on a specified layer. Otherwise the script will show a **no selection** error.

<!-- ROADMAP -->
## Roadmap

<!-- CONTRIBUTING -->
## Contributing

Contributions are what makes EDA solutions the ultimate dream team. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
6. If the changes made are much more awesome, then the request would be approved and merged into the main branch. 

<!-- CHANGE LOG -->
## Change log

<!-- LICENSE -->
## License

Not to be distributed to anyone outside EDA solutions. 

<!-- CONTACT -->
## Contact

James Mutumba  - jamesmutumba@eda-solutions.com

Project Link: [overlapping_area](https://github.com/EDA-Solutions-Limited/overlapping_area)
