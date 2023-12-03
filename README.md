# ADS-Project
This project is an integral part of the Algorithms and Data Structures course. It consists in the identification of a real world problem, the design of the solution of the problem through computer programming, the development of the minimum viable product of this solution and its presentation. 

Introduction to EasyHome.

Welcome to EasyHome, your go-to app for simplifying the apartment search process and connecting with the perfect roommate. Although designed for international users, it can be used by anyone. EasyHome is dedicated to helping you find not just a place to live, but also someone that complemets to your lifestyle. Explore our user-friendly platform to discover ideal apartments and compatible roommates. EasyHome relies on the lastest algorithmic techniques, using quicksort, binary search, trees, and OOP, to find an appartment that checks all of your boxes.

<img width="380" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/b34854b0-e568-4ade-b131-94684540777d"> <img width="389" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/938e447b-a775-4ba2-9ce4-178fc5cfe0a4">


What does our program do?: 

We created a database filled with many appartments available, each one with unique features like price, location, and number of rooms/bathrooms, etc. The user will be asked to input the price range they are willing to pay as well as other especifications. Our code will use quicksort and binary search algorithms to create a new dataset to quickly narrow down the housing options using the inputs as a reference. Then, the user will again be asked some question related to the type of person they are looking for to be their roommate (age, gender, personality type, etc.). Our program will take into account both the houses selected and the roomate characteristic to output the ideal solution. The information about the other users that will be possible matches are recorded previously using a survey and added into a datset.

<img width="400" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/fe39b213-7144-441b-87f8-2de448386cb8">


Algorithms:

What is quicksort?

It is an algorithm that sorts an array using a [Divide and Conquer](https://www.geeksforgeeks.org/divide-and-conquer/) approach. How does it work? It randomly selects a number that goes from 0 to the number of elements in the list-1. This number will correspond to the position where the pivot is located in the list. The array is then partitioned into two sub-lists, one with elements smaller than the pivot, and, the other  with elements that are greater. This process is applied recursively to each sub-list, using different pivots each time, until reaching sub-arrays with one or no elements. Through this iterative or recursive method, the entire array becomes sorted. This algorithm will be applied when wanting to create the narrowed version of the appartments dataset - by sorting by price (Quicksort).

What is Binary Search?

Is an algorithm for finding a target value within a sorted array. It compares the target value to the middle element of the array and eliminates half of the remaining elements based on the comparison. This process repeats until the target is found or the search space is empty. To gain a better understanding go to [GeeksForGeeks](https://www.geeksforgeeks.org/binary-search/).

Datasets:

The datasets containing all the appartments information can be found in: 

The information about the students/users registered in our app comes from a Google forms survey: [here](https://docs.google.com/forms/d/e/1FAIpQLSdSy_nhyyBdQ4avUhnSphkRRb2X5sBGxJgc9Er5y6-B6ADczA/viewform?).

You can download the answers of the survey recorded as a dataset from: 

# INSTRUCTIONS:
For those interested in understanding and exploring the algorithms used, the complete version of the code is found in the 'CODE' foulder inside this repository. This code is done using Python, therefore it is advised to open it using a Python environment such as Pycharm. To install Pycharm click on [Download](https://www.jetbrains.com/es-es/pycharm/). 

Then, open it in your device, create a new project and give it a name, for example 'PycharmProject'. 

<img width="200" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/3c4dd310-1cc3-4582-8164-c51fb025cb70">

After, download the datasets, and open your documents foulder on your device. You have to move the datasets from Downloads to your new 'PycharmProjects' foulder.

<img width="60" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/61110ccb-ffe9-420e-99ad-d3ad9dc27e26">  <img width="277" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/328ec29c-e69e-4e72-91be-a9967f2697a3">

Now, when you enter Pycharm, you will see the datasets appear here:
<img width="200" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/f32cea42-d201-4d4e-9311-b45311be4127">

Then, copy the code into your new project and run it. The pycharm console will pop up and show if there are any errors, or in case it runs correctly,  show the questions for the user.
<img width="200" alt="image" src="https://github.com/emilyedgars/ADS-Project/assets/152634583/3c776bc9-4120-434d-a352-1440051acecc">

# CONTACT US:
For further information or help please contact:
jruiz.ieu2022@student.ie.edu

This README file will constantly be updated by the developers of the project: Naji, Marianna, Emily, Omar, Jessie and Julia.


