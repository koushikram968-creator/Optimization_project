# **Optimal Shipment Planning Using Integer Linear Programming (ILP)**

---

## **Team Details**
**Team Name:** Koushik n co  
**Member 1:** Ram Koushik  
**Member 2:** Mithun Kumar  
**Member 3:** Sohan Reddy  

---

## **Project Title**  
**Optimal Shipment Planning Using Integer Linear Programming (ILP)**

---

## **Project Description**  
This project optimizes the delivery of goods from multiple warehouses to multiple customers while minimizing transportation cost.  
The model considers:
- Warehouse supply limits  
- Customer demand requirements  
- Route capacity constraints  
- Shipping costs and distance-based fuel weight  
- Integer shipment quantities  

The ILP solution finds the cheapest feasible shipment plan that satisfies all constraints.

---
**Project Structure**

project/
│── code/
│   ├── main.py
│   ├── generate_dataset.py
│   ├── ilp_solver.py
│   ├── utils.py
│── data/
│── output/
│── runs/
│── README.md


## **Libraries Used**
- Python 3  
- NumPy  
- Pandas  
- PuLP (CBC Solver)  
- Matplotlib  
- Seaborn  
- OS & JSON modules  

---

## **Installation**
Install required dependencies using:


---

## **How to Run**

### **1. Navigate to the project folder**
cd project

### **2. Run the main program**
python code/main.py

### **3. Provide input when asked**
- Number of warehouses (1–15)  
- Number of customers (1–15)  
- Distance weight (0–1)  

### **Example Input**
Number of warehouses: 4
Number of customers: 6
Distance weight: 0.7
