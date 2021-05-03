# visual-cov2019

This repository contains a code to visualize data related to the COVID-19 pandemic, which is the final project of a coursera course, *[Mastering Programing with MATLAB](https://www.coursera.org/learn/advanced-matlab-programming)*. I share this code for the purpose of exchanging experience, please do **NOT** submit it as your own project to corsera. 

- The code files are: 

```
.
├── Country.m —— [class of Country]
├── cov19.mlapp —— [MATLAB app]
├── covid_data.mat —— [COVID-19 pandemic data]
├── example.PNG
├── LICENSE
├── README.md
└── State.m —— [class of State]
```



- It's wrote in the project description: 

> The goal of the final project is to create a MATLAB program that processes and visualizes COVID-19 pandemic data. The data (obtained from the Coronavirus Resource Center at the Johns Hopkins University) is available from the .mat file attached below. Once you load it, you will get a single variable called covid_data that is a large cell array. ... Each data cell for a given country and date contains a 2-element vector of doubles: the first element is the cumulative case count, while the second is the cumulative number of deaths. 

> Your program must convert this data into a set of objects: one object per country and state. States should be contained by their countries. Countries could be stored in a vector of country objects in the app itself. Another way is to create an instance of the same class you use for countries and states, call it global, and have it store all the countries. The app would then contain the single global object as a property. This option would create a 3-level hierarchy: the global object stores data for the entire world and a vector of country objects, while the objects of countries that have states in the database would store their corresponding states. Again, you can use the same class definition for all three kinds of objects because they store essentially the same kind of data. 

- Below is a screen shot of an example implementation. 

![example](/example.PNG)


Further, please check:

[1] *[Coursera](https://coursera.org/share/41748f1691f5fea1cbfcbfba67fa1685)*

[2] *[Mastering Programing with MATLAB](https://www.coursera.org/learn/advanced-matlab-programming)*
