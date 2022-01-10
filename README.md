<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/akash5852/chip8-emulator">
    <img src="https://github.com/akash5852/akash5852/blob/main/icons/logos/PikPng.com_video-game-icon-png_5100842.png" alt="Icon"height="60">
  </a>

  <h3 align="center">C++ CHIP-8 emulator</h3>

  <p align="center">
    An emulator written in C++ based on Austin Morlans Building a CHIP-8 Emulator
    <br />
    <a href="https://github.com/akash5852/chip8-emulator"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/akash5852/chip8-emulator/issues">Report Bug</a>
    ·
    <a href="https://github.com/akash5852/chip8-emulator/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#screenshots">Screenshots</a>
    </li>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#thank-you">Special Thanks</a></li>
  </ol>
</details>

## Screenshots

<p width="600">
  Tetris:
  </br>
    <img src="https://github.com/akash5852/chip8-emulator/blob/master/img/tetris.jpg" alt="tetris" width="600" >
  
    
</p>

<!-- ABOUT THE PROJECT -->
## About The Project
I have always been fascinated about emulators, and they are a big reason I got into computers in the first place. I wanted a way to apply my skills as a Computer Engineer, and came to the conclusion to create an emulator. I want to create a gameboy emulator in the future, but for now I started off small with a CHIP-8 emulator instead, only having 32 Opcodes to worry about. I came across Austin Morlan's guide on how to achieve this, and created my first emulator.

## Getting Started

### Installation

Clone the repo
   ```sh
git clone https://github.com/akash5852/chip8-emulator
   ```
 Get <a href="https://wiki.libsdl.org/Installation">SDL2</a>, installation varies based on OS.
 
 If using a Linux however, use this command
 ```sh 
sudo apt-get install libsdl2-dev
 ```
 
 Compile using
 ```sh
g++ -Isrc/Include -Lsrc/lib -o chip8 *.cpp -lSDL2main -lSDL2
 ```
<!-- ROADMAP -->

 Obtain ROMS for CHIP-8 and run ROMS using,
 ```sh
./chip8 10 n x.ch8
 ```
 With n being the delay in miliseconds, I recommend 3 and x being the ROM name.
## Roadmap

See the [open issues](https://github.com/akash5852/chip8-emulator/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License.



<!-- CONTACT -->
## Contact

Akash Sharma - shara98@mcmaster.ca

Project Link: [https://github.com/akash5852/chip8-emulator](https://github.com/akash5852/chip8-emulator)

## Thank You
Enormous thanks to Austin Morlan's 'Building a CHIP-8 Emulator'!

You can find it here: [https://austinmorlan.com/posts/chip8_emulator/](https://austinmorlan.com/posts/chip8_emulator/)

