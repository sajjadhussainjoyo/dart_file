void main() {
  // 1-Sep-24 (Class 04 Dart)
  // TOPICS COVERED
  // NESTED IF ELSE
  // LIST ITS DATA TYPES AND METHODS
  // Map

  // last class if else
  // Git and GithUB

  // Class Task 01  Given time (10-15 mins)
  //Task Details: Login program if else ka through user sa input then match
  //kareinga user na sahi email aur password put kia
  //user na agar dono galat dal raha tou email galat hai aur
  //email or username (login hojaiga username and email sa)
  // password aik  email is incorrect password is incorrect
  // agr dono theek tou login successful

  // stdout.write('Enter your email or username....');
  // var email = stdin.readLineSync();

  // stdout.write('Enter Password....');
  // int password = int.parse(stdin.readLineSync()!);

  // if (email == 'sajjadhussain@gmail.com') {
  //   print('Email Successful');
  //   print('Invalid Email');
  // } else if (password == 123) {
  //   if (password == 123) {
  //     print('');
  //   }
  // } else {
  //   print('Successful Login');
  //   print('Invalid ');
  // }

  // MAP & ITS DATATYPES
// INDEX 0 SA MAGAR COUNT KRTA HWA 1 SA
// FIRST END REPLACEMENT
//

// Simply print List numbers
  List mylist = ['sajjad', 12345, 'vscode'];
  print(mylist);

// Print list index
  print(mylist[1]);

  // List Methods
  //i. first, ii.last, iii. elementAt(), iv.length
  print(mylist.first);
  print(mylist.last);
  print(mylist.elementAt(1));
  print(mylist.length);

// List methods
// v. add() vi. clear() vii. removeAt() viii. replaceRange()
// ix. sort()

// Add method i. add() ii. addAll() iii. insert() iv. insertAll()
  mylist.add('hello');
  print(mylist);

// Clear method
  mylist.clear();
  print(mylist);

// Remove method i. remove() ii. removeAt() iii. removeLast()

// Remove method
  var vals = [1, 3, 4, 5];
  vals.remove(3);
  print(vals);

// RemoveAt
  vals.removeAt(2);
  print(vals);

// Remove Last
  vals.removeLast();
  print(vals);

  // isEmpty() isNotEmpty()

// List removeRange method
  List numberList = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  numberList.replaceRange(1, 5, [11, 12, 13, 14, 15]);
  print(numberList);

  // List method reversed() ismai ham ek variable naya intialize karwa
  // kay phir reversed list laga deinga
  var listTwo = numberList.reversed.toList();

  // list 2 ways to clear method
  // myList.clear();
  // myList = [];

//Map
  // data store in keys value kesa access key ka zariyah sa hoga
  // sir ko reminder delana string concatenation aur data
  // map aur object ek hi cheez hai
  //array aur list ek hi cheez hai

  var data = {'name': 'sajjad', 'occupation': 'student'};
  print(data);
  print(data.keys);
  print(data.values);

// 2 ways to clear Map
  data.clear();
  data = {};
}
