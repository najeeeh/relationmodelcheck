# relationmodelcheck

Hotel (Hotel_Id, Hotel_name, #type_id)(type is a composed attribute 1NF)
----
Type (type_id, type_name)
-----
Employee (Employee_Id, Employee_Name, Employee_Speciality, #Hotel_Id, #Leader_id)
-----
Room (Room_id, Floor,#Hotel_Id,#Category_id)
-----
Category (Category_Id, Category_Name, Price, Beds_numbers)
