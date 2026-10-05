# Trivia-Quiz
C++ day 6: conditional code. integrating if statements, input, and incrementing

#include <iostream>
#include <string>
int score=0;
int answer1;
int answer2;
std::string answer3;

int main () {
  std::cout<<"Q1) What is the name of the worlds largest river?\n";
  std::cout<<"1) Missouri River\n";
  std::cout<<"2) Nile\n";
  std::cout<<"3) Amazon River\n";
  std::cout<<"4) Yangtze River\n";
  std::cout<<"Answer (as number): ";
  std::cin>>answer1;
  if (answer1 == 3) {
    ++score;
  }
  std::cout<<"Q2) How many bones are in the human body? 🦴\n";
  std::cout<<"1) 92\n";
  std::cout<<"2) 150\n";
  std::cout<<"3) 206\n";
  std::cout<<"4) 10\n";
std::cout<<"Answer (as number): ";
std::cin>>answer2;
if (answer2 == 3) {
  ++score;
}
std::cout<<"Q3) What food never spoils? 😷\n";
std::cout<<"Type your answer: ";
std::cin>>answer3;
if (answer3 == "honey") {
  ++score;
}
std::cout<<score;
}
