# Student-Management-Systen
Student Management System using Encapsulation and Abstration..


#include <iostream>
using namespace std;
class Student
{
private:
    int studentId;
    string studentName;
    double cgpa;

public:
    void setstudentId(int studentId)
    {
        this->studentId =studentId;
    }
    void setstudentName(string studentName)
    {
        this->studentName= studentName;

    }
    void setcgpa (double cgpa)
    {
        this-> cgpa=cgpa;
    }

    int getstudentId()
    {
        return studentId;
    }
    string getstudentName()
    {
        return studentName;
    }
    double getcgpa()
    {
        return cgpa;
    }
};

int main()
{
    Student s1;
    s1.setstudentId(314);
    s1.setstudentName("Rahim");
    s1.setcgpa(3.50);

    cout<<"Student ID:"<<s1.getstudentId() <<endl;
    cout<<"Student Name:"<<s1.getstudentName()
<<endl;
    cout<<"Student CGPA:"<<s1.getcgpa() <<endl;
    return 0;
}

