
\\\\\\

int main()
{
  int magic;  // magic number
  int guess;  // user's guess

  magic = rand(); // get a random number
  
  cout << "Enter your guess: ";
  cin >> guess;

  if(guess == magic) 
	  // Notice the "==" operator, which compares two values.   
	  cout << "** Right **";
  cout << "The magic number was: " << magic << endl;
  return 0;
}

There are no changes