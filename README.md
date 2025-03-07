# Shape Calculator (Area & Volume)
## Author: Krrish Sinha  
## PRN: 23070126063
## Batch: 2023-2027 

## 📌 Description  
This is a **Java Menu-Driven Program** to calculate the **Area, Perimeter, and Volume** of various geometric shapes.  
It follows **OOP principles** using **Abstract Classes** and **Interfaces**.

## 📂 Project Structure  

## 📌 Features  
✅ **Abstract Class `Shape`**: Defines methods for `calculateArea()` & `calculatePerimeter()`.  
✅ **Interface `Volume`**: Implements `calculateVolume()` for 3D shapes.  
✅ **Menu-Driven Program**: User can **select a shape** and enter **measurements**.  
✅ **Separate Java Files**: Follows modular programming for **better maintainability**.  

## 📌 Shapes & Their Implementations  
| Shape               | Type       | Implements        |  
|---------------------|-----------|------------------|  
| Circle             | 2D Shape  | Shape (Abstract) |  
| Rectangle          | 2D Shape  | Shape (Abstract) |  
| Square            | 2D Shape  | Shape (Abstract) |  
| Sphere            | 3D Shape  | Shape + Volume   |  
| Cylinder          | 3D Shape  | Shape + Volume   |  
| Equilateral Pyramid | 3D Shape  | Shape + Volume   |  

## 📌 How to Run?  
### 🔹 Clone the Repository  
```bash
git clone https://github.com/yourusername/ShapeCalculator.git
cd ShapeCalculator/src
====== Shape Calculator ======
1. Circle
2. Rectangle
3. Square
4. Sphere
5. Cylinder
6. Equilateral Pyramid
7. Exit
Enter your choice: 1
Enter radius of Circle: 5
Area: 78.54
Perimeter: 31.42
