// Java program to demonstrate
// the use of hasNext() method

// Importing java input output classes
// Importing all classesfrom
// java.util package
import java.io.*;
import java.util.*;

// Class
class GFG {

	// Main driver method
	public static void main(String[] args)
	{
		// Creating an ArrayList
		// Declaring the ArrayList
		ArrayList<String> list = new ArrayList<String>();

		// Adding (appending) new elements at
		// the end of the List
		// Custom inputs
		list.add("Geeks");
		list.add("for Geeks");

		// Declaring the Iterator
		Iterator<String> iterator = list.iterator();

		// Printing hasNext() values
		// Prints true because iterator has two more values
		System.out.println(iterator.hasNext());

		// Go to next value using next() method
		iterator.next();

		// Prints true because iterator has one more values
		System.out.println(iterator.hasNext());

		// Go to next value using next() method
		iterator.next();

		// Prints false because iterator has no more values
		System.out.println(iterator.hasNext());
	}
}



// Java program to demonstrate
// the use of next() method

// Importing java input output classes
import java.io.*;
// Importing all classes from
// java.util package
import java.util.*;

// Class
class GFG {

	// Main driver method
	public static void main(String[] args)
	{
		// Creating an ArrayList
		// (Declaring ArrayList of String type)
		ArrayList<String> list = new ArrayList<String>();

		// Adding elements to above List at
		// the end of the list
		// Custom inputs
		list.add("Element1");
		list.add("Element2");
		list.add("Element3");

		// Declaring the Iterator
		Iterator<String> iterator = list.iterator();

		// Printing values showcasing next() method which
		// shows traversal over elements
		// only in forward direction

		// Prints first element traversed
		System.out.println(iterator.next());

		// Prints the succeeding element
		System.out.println(iterator.next());

		// Prints another element succeeding
		// to previous element
		System.out.println(iterator.next());
	}
}
