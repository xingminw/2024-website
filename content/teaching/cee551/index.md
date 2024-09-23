---
title: CEE 551 Traffic Science
summary: Graduate-level course of civil engineering at the University of Michigan (2022 Fall, 2023 Fall, and 2024 Fall).
date: 2024-08-01
type: docs
math: false
toc: true
tags:
  - Traffic
image:
  caption: 'CEE 551 Traffic Science'
---

I served as the co-instructor for CEE 551 Traffic Science at the University of Michigan during the Fall semesters of 2022, 2023, and 2024.

- 2021 and 2023 Fall: traffic operation (teaching evaluation for 2023 Fall: Course rate 4.6/5.0 and instructor rate 4.9/5.0)
- 2024 Fall: traffic flow model

## Introduction

This course provides an introduction to the fundamentals of urban traffic science and engineering, covering topics such as traffic flow theory, traffic control, and traffic simulation. Students will learn to apply computer simulation models to the design and operation of traffic systems. The course will also explore the next generation of traffic systems, including connected and automated vehicles.

## Main content

- Traffic flow model: traffic state variables, fundamental diagrams, LWR model, and cell transmission model;
- Traffic operation: traffic signal control;
- Traffic simulation: basic car-following and lane-changing models, SUMO simulation, etc.

## Course materials

Here are the most recent slides I use (2024) to teach the traffic flow theory. Feel free to use these slides as long as you acknowledge my efforts. Email me if you find them useful and need the PowerPoint Version:

- [Lecture 1 - Traffic flow variables and their relationships](slides/TrafficFlowLecture1.pdf)
- [Lecture 2 - LWR model and its solution](slides/TrafficFlowLecture2.pdf)
- [Lecture 3 - Shockwave theory and examples](slides/TrafficFlowLecture3.pdf)
- [Lecture 4 - Godunov scheme and cell transmission model](slides/TrafficFlowLecture4.pdf)

I have also integrated my latest research into this course. While traditional traffic flow theory is primarily based on the LWR model, which relies on fixed-location detector data, this new lecture introduces vehicle trajectory data, even at low penetration rates, as an emerging data source. I then present the **probabilistic time-space model**, designed specifically to capture traffic flow dynamics near signalized intersections.

- [Lecture 5 - CTM implementation and trajectory data](slides/TrafficFlowLecture5.pdf)
- [Lecture 6 - PTS model near signalized intersections](slides/TrafficFlowLecture6.pdf)

In 2022-2023, I taught the traffic signal control module using slides adapted from those developed by my PhD advisor, Dr. Henry Liu. Many of the slides are based on his original materials, and I plan to update them further in the future.

- [Lecture 1 - Traffic Signal Control Basics](slides/TrafficSignalLecture1.pdf)
- [Lecture 2 - Traffic Signal Parameters](slides/TrafficSignalLecture2.pdf)
- [Lecture 3 - Traffic Signal Design](slides/TrafficSignalLecture3.pdf)
- [Lecture 4 - Level of Service Analysis](slides/TrafficSignalLecture4.pdf)
- [Lecture 5 - Coordination](slides/TrafficSignalLecture5.pdf)
- [Lecture 6 - ATSC and Traffic Control with CAV](slides/TrafficSignalLecture6.pdf)