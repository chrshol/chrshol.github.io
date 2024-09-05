---
layout: project
type: project
image: img/hotel-booking.jpg
title: "Hotel Booking App"
date: 2021
published: true
labels:
  - Java
  - FXML
summary: "My teammate and I developed a Hotel Booking App for our TDT4100: Object-Oriented Programming course at the Norwegian Univeristy of Science and Technology"
---

The goal of this project was to get familier with object oriented programming using Java. We worked in pairs of two and we were free to choose whater project we wanted. My teammate and I landed on making a Hotel Booking App. This project was my first team coding project, and gave me the opportunity to learn pair programming and gain experience with using Git.


In this project me and my partner developed a functional app consisting of several classes. We ensured that all classes encapsulate tehir state and include validation when state changes occur. The user interface was created using FXML, supported by Controller and App classes. Additionally, the app features the ability to read from and write to a file, making it useful for storing data such as a list of all bookings. Appropriate error handling was implemented throughout the app, and we created a set of JUnit tests to verify that the app's functionality works as intended

Here is a photo illustrating how the app looks like:

<p align="center">
  <img src="../img/hotel-booking.png" width="400">
</p>


```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
