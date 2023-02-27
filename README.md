#include <stdio.h>

struct student {
  char name[50];
  int roll_no;
  float marks1;
  float marks2;
  float marks3;
};

int main() {
  struct student s;
  
  printf("Enter name of student: ");
  scanf("%s", s.name);
  
  printf("Enter roll number: ");
  scanf("%d", &s.roll_no);
  
  printf("Enter marks in subject 1: ");
  scanf("%f", &s.marks1);
  
  printf("Enter marks in subject 2: ");
  scanf("%f", &s.marks2);
  
  printf("Enter marks in subject 3: ");
  scanf("%f", &s.marks3);
  
  printf("\nStudent Details:\n");
  printf("Name: %s\n", s.name);
  printf("Roll Number: %d\n", s.roll_no);
  printf("Marks in subject 1: %.2f\n", s.marks1);
  printf("Marks in subject 2: %.2f\n", s.marks2);
  printf("Marks in subject 3: %.2f\n", s.marks3);
  
  return 0;
}
