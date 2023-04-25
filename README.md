# collecttion
advance arrays;
package mypackage4;

import java.util.ArrayList;
import java.util.HashSet;
import java.util.LinkedHashSet;
import java.util.LinkedList;
import java.util.Vector;

//import java.util.ArrayList;
//import java.util.HashSet;
//import java.util.Iterator;
//import java.util.LinkedHashSet;
//import java.util.LinkedList;
//import java.util.Vector;
import java.util.*;
public class Collection {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		//Creating arraylist
		System.out.println("Arraylist");
		ArrayList<String>city=new ArrayList<String>();
		city.add("Delhi");
		city.add("Kota");
		city.add("Deoria");
		city.add("Bangluru");
		System.out.println(city);
		//creating Vector;
		
		System.out.println("\n");
		System.out.println("vector");
		Vector<Integer> vec=new Vector();
		vec.addElement(15);
		vec.addElement(20);
		System.out.println(vec);
		// creating linkedlist;
		
		System.out.println("\n");
		System.out.println("Linkedlist");
		LinkedList<String> name=new LinkedList<String>();
		name.add("Ramesh");
		name.add("Dinesh");
		name.add("Suresh");
		name.add("Mahesh");
		System.out.println(name);
		Iterator<String> itr=name.iterator();
		while(itr.hasNext()) {
			System.out.println(itr.next());
			
			// creating hashset;
			System.out.println("\n");
			System.out.println("HashSet");
			HashSet<Integer> set=new HashSet<Integer>();
			set.add(12);
			set.add(50);
			set.add(22);
			set.add(45);
			System.out.println(set);
			
			System.out.println("\n");
			System.out.println("LinkedHashSet");
			LinkedHashSet<Integer> set2=new LinkedHashSet<Integer>();
			set2.add(15);
			set2.add(14);
			set2.add(13);
			set2.add(12);
			System.out.println(set2);
		}
		
		
		

	}

}
