using System;
class EmployeeData
{
    static void Main()
    {
        Console.WriteLine("EMPLOYEE DATA REGISTERING, STARTED: \n \n First Name:");
        string firstname = string.Intern(Console.ReadLine());
        Console.WriteLine("Last Name:");
        string lastname = string.Intern(Console.ReadLine());
        object fullname = firstname + "  " + lastname;
        Console.WriteLine("Age:");
        string age = string.Intern(Console.ReadLine());
        Console.WriteLine("Gender:");
        string gender = string.Intern(Console.ReadLine());
        Console.WriteLine("Personal ID:");
        string id = string.Intern(Console.ReadLine());
        Console.WriteLine("Unique Employee Number:");
        string number = string.Intern(Console.ReadLine());

        Console.WriteLine("Details: \n Full Name: {0} \n Age: {1} \n Gender: {2} \n Personal ID: {3} \n UE Number: {4} \n", fullname, age, gender, id, number);
    }  
}
