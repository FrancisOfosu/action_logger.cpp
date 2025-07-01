/*
  Program: Action Logger
  Author : Francis Ofosu
  Date   : [July 1, 2025]
  Purpose: This program prompts the user for their full name, an action performed, and  the time the action occurred.
		   It then outputs an audit-style log entry in the format:
		   [AUDIT LOG] 10:30 AM - Francis Ofosu performed 'updated firewall rules'
*/


#include<iostream>
#include<string>
int main()
{
	// Declare variables to store user name, action performed, and the time the action was performed
	std::string fname;
	std::string action;
	std::string time;

	// Prompt user for their full name
	std::cout << "Enter your full name: ";
	std::getline(std::cin, fname);			// Read full name, including spaces

	// Prompt user for the action they performed
	std::cout << "Enter action performed: ";
	std::getline(std::cin, action);			// Read full description of the action

	// Prompt user for the time the action occured
	std::cout << "Enter the time the action occurred (e.g. 10:30 AM): ";
	std::getline(std::cin, time);			// Read full time, including spaces

	// Output a formatted audit log entry
	std::cout << "[AUDIT LOG] " << time << " - " << fname << " performed " << "'" << action << "'" <<std::endl;
	return 0;
}