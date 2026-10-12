# connect-four-tcp-server
Java-based Connect Four game server with TCP socket communication and a rule-based opponent.
# Connect Four TCP Server

A Java implementation of a networked Connect Four game,
developed as part of a university programming assignment
at the Technical University of Denmark (DTU).

## Features

- TCP socket communication
- Turn-based gameplay
- Rule-based computer opponent
- Move validation
- Horizontal, vertical and diagonal win detection

## Technologies

- Java
- TCP/IP
- Socket Programming

## Implementation

The server uses a prioritized decision-making algorithm
to select moves. It first checks for winning opportunities,
then attempts to block the opponent before considering
other strategic moves.