# Gym Exercises Website

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)


- [API Integration](#api-integration)



## Introduction

The **Gym Exercises Website** is a React-based web application designed to help fitness enthusiasts and gym-goers discover a wide range of exercises to incorporate into their workout routines. It connects to the **ExerciseDB** API via **Rapid API** to fetch exercise data and provides users with detailed information about each exercise, including descriptions, images, and muscle groups targeted.

Whether you're a beginner looking for basic exercises or an experienced fitness enthusiast seeking to diversify your workout routine, this website has you covered. Explore and learn new exercises to achieve your fitness goals!

## Features

- **Exercise Search**: Easily find exercises by name or keyword.
- **Exercise Details**: View detailed information about each exercise, including descriptions, images, and muscle groups worked.

- **Responsive Design**: Enjoy a seamless experience on both desktop and mobile devices.



## Getting Started

### Prerequisites

Before you get started, make sure you have the following prerequisites installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

## API Integration

This website uses the **ExerciseDB** API via **Rapid API** to fetch exercise data. To integrate the API into your project, follow these steps:

1. Sign up for a [Rapid API](https://rapidapi.com/) account if you don't have one.

2. Subscribe to the **ExerciseDB** API on Rapid API and obtain your API key.

3. In your project, create a `.env` file in the root directory and add your Rapid API key:

   ```
   REACT_APP_RAPIDAPI_KEY=YOUR_API_KEY_HERE
   ```


