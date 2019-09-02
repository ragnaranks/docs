[Back to Index](./index.html)

## Contents
- [Introduction](#introduction)

## Introduction
A common scenario for players when browsing servers is to find out whether the server is online and the amount of 
players playing on such server at a glance, we aim to solve this problem by introducing a feature we call `Heartbeats`.
At an overview of the system it is an essential element to the website that retrieves the server status for display

## Checkups
We define a checkup as being an element that can be checked through the website, each listing has a heartbeat, and each
heartbeat has a checkup that occurs every `10 Minutes`, as of current we only support one type of checkup

- Flux Control Panel
    - We process the contents of `status.xml` found on your control panel at the location 
    `/?module=server&action=status-xml` as a means of identifying the player count, login, char and map status.

## Preview
![alt text](./images/heartbeat/preview.png "Step 6: Completed Detailing.")

[Done? Lets go Back to Index](./index.html)