[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Ikram Yahya
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
public:
    std::string model;
    int year;


    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;


    myCar.displayDetails();

    return 0;
}

```
class Car {
private:
    int year;
    string model;
    string color;

public:
    string getmodel(){
    return model;
    }

    string getyear(){
    return year;
    }
    
    string getcolor(){
    return color;
    }
    




    void setModel(string newModel) {
        model = newModel;
    }

    void setYear(int newYear) {
        year = newYear;
    }

    void setColor(string newColor) {
        color = newColor;
    }

  
    void displayDetails() {
        std::cout << "Model: " << getModel() << ", Year: " << getYear() << ", Color: " << getColor() << std::endl;
    }
};

int main() {
    
    Car myCar;

    myCar.setModel("Toyota Camry");
    myCar.setYear(2022);
    myCar.setColor("Blue");

    
    myCar.displayDetails();

    return 0;
}






