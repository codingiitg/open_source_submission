Omkar Chaudhari
===================
## 200122042
___
## Coding Week Schedule


Event Name | Event Date | Gone through the Resources
--- | --- | ---
Open Source | 10/05/2021 | **YES**
Competitive Coding | 11/05/2021 |	NO
Design | 12/05/2021 |	NO
Game Development | 13/05/2021 |	NO
Web Development |	14/05/2021 | NO
Machine Learning | 15/05/2021 | **YES**
App Development | 16/05/2021 | NO
___
## Code to calculate sum of ASCII values of my full name
```C++
#include <iostream>
using namespace std;

void main() 
{
    int i;
    string name = "Omkar Ganesh Chaudhari";
    int sumofASCII=0;

    cout << "Full Name: " << name;

    for(i=0; i<name.length(); i++)
    {
      if(name[i]==' ')
      {
        continue;       //Spaces get ignored
      }else
      {
        sumofASCII = sumofASCII + int(name[i]);     //type casting, every character has a assigned ASCII value
      }
    }

    cout << "\nSum of ASCII Value of characters of my name(Case Sensitive) of " << name << " is: " << sumofASCII;
}
```
___
![Coding Week](https://github.com/codingiitg/open_source_submission/blob/main/Group%2095.png)
___
## Coding Club Logo


![Coding Club Logo](https://github.com/codingiitg/open_source_submission/blob/main/coding-club%20logo.png)
___

## Interests:

Coding has been my pastime for several years now, I have learnt HTML, CSS, JAVA(Upto Data Structures), C(Upto Stacks) and Python over the course of my school and college. I recently picked up quite a bit of interest in machine learning and its applications. I created 2 projects in machine learning:


1. An image classifier that classifies planes, cars and bikes, or any image categories I feed it.
2. A project that uses sentimental text analysis to classify movie review as positive or negative. The movie reviews were fed to it through a kaggle dataset of IMDB Reviews.

I have some interest in game development too, I have used blender a fair amount to edit my youtube videos and create thumbnails.
Overall I have yet to explore all verticals, but I am extremely enthusiastic about ML/AI and Game Development in particular.
