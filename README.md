Stuff
=====

PPT

  // Variables
	int Sprime = 0; // this is the user variable s, and must be s>t>=1
	int Tprime = 0; // this is the user variable t, and must be s>t>=1

	// Program Purpose
	cout <<"This program uses the Pythagorean Triples Theorem \nto generate Primitive Pythagorean Triples. \n\n";
	cout <<"**********************************************************\n\n";
	// User instructions
	cout <<"**********************************************************\n";
	cout <<"Choose two numbers s and t satisfying the conditions\n";
	cout <<"of s greater than t, and t is greater than or equal to 1.\n\n";
	cout <<"Where s and t are any odd integers with no common factors.\n";
	cout <<"**********************************************************\n\n\n";
	// Prompt user for s and t
	cout <<"***Please enter an s variable:\n";
	cin >> Sprime; 
	cout << endl << endl; 
	cout <<"***Please enter a t variable:\n";
	cin >> Tprime; 
	cout << endl << endl; 

	// PPT Variables
	int Aprim = (Sprime*Tprime); // the a variable
	int Ssquared = Sprime*Sprime; // s squared
	int Tsquared = Tprime*Tprime; // t squared
	int Bprim = (Ssquared - Tsquared)/2;
	int Cprim = (Ssquared + Tsquared)/2; 

	// Display
	cout <<"**********************************************************\n";
	cout <<"You entered " << Sprime <<" for s, and " << Tprime << " for t. " << endl << endl; 
	cout <<"This gives a value of " << Aprim <<" for a, and " << Bprim <<" for b." << endl;
	cout <<"and a c value of " << Cprim << endl << endl;
	cout <<"**********************************************************\n\n\n";
	cout <<"This gives us a Primitive Pythagorean Triple of:\n";
	cout <<"(a, b, c) = (" << Aprim <<", "<< Bprim <<", "<< Cprim <<")\n\n\n";
	cout <<"**********************************************************\n\n\n";

	return 0;

}
