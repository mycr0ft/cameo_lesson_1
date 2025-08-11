# Cameo/MagicDraw plugin development - Lesson 1

This is the first lession of how to develop a plugin for Cameo/MagicDraw. At the end of the lession you will have an environment and a very simple - hello world - example.

# Requirements

- Cameo/MagicDraw 2024x Refresh 3
- Java JDK 21
- Maven mvn 

# Usage

## Check out the repository

`git clone https://github.com/mycr0ft/cameo_lesson_1.git`

## Configure environment variable

Configure Cameo/MagicDraw root directory according to local setup, for example:

`set CAMEO_ROOT /Users/Insert_Your_Path/Cameo_EA_2024x`

`export CAMEO_ROOT`


## Build project

`mvn package`

## Extract into Cameo plugins folder

Extract `target/hu.modeldriven.cameo.lesson1.zip` into `CAMEO_ROOT/plugins`

## Restart

Restart CAMEO
