# I2C

An application to control an I2C display on a Raspberry Pi.
This application is meant to be multi-use software, with features ranging from a bus line analyser, a bus delay analyser, a generative AI command line, weather reports, saving notes and much more.

This is a starter project, with the goal of expanding everything later on to, let's say, an e-ink display or a small LCD.
After some tinkering with GTK, I decided to switch to Qt for the GUI application.

The program is multi-platform and even supports a web console.

MAIN USE OF THE PROGRAM:
the main feature of the program is the ability to control an I2C display really extensively and to be able to do a lot of things with it.

CURRENT FEATURES:

-   Weather display
-   Randomly generated greeting quote (I still don't really know what to do about that; I could add a joke-of-the-day system or something like that)
-   A button-powered Pomodoro timer
-   Some sort of clock mechanism that adds an alarm clock, a timer and a stopwatch
-   System monitor dashboard (CPU, RAM, disk, temperature, ...)
-   Speech command center
-   Generative AI model that uses Meta's Llama
-   Currently playing audio
-   Voice-based notes
-   To-do list integration based on your personal calendar

A nice idea for the future is to make it easily installable and configurable, without too much tinkering needed.
At the moment, the software only supports a CLI version.

Support will be kept to Linux and macOS for now.

<center>---

                     I2C CONTROLLER GUIDE

</center>---

This program is designed to control an LCD1602 using Python. It supports
a GUI and a CLI interface, and at the moment it is only Linux-compatible.

You will need to have a couple of dependencies ready on your device to use the software.

---

The software supports multiple features, ranging from a note-saving system (which is actually a fun way of saying displaying something on the screen and saving the output for later use) to speech transcription and system readings.

The main way of using the software is the CLI. Run the main.py file and you will see the options pop up; after you choose them, they will run automatically. The CLI is still the recommended way of using it, simply because it's meant for controlling a Raspberry Pi through an SSH session.

---

                Installation Guide

Install the executable and run it.
![Program Preview](https://github.com/nasrlol/I2C-CONTROLLER/preview.png)
