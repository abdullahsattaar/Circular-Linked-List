# Circular-Linked-List
C++ code of Circular Linked List with Iterator with all operators, also template node class implemented.

1.	Implement a template class ‘Node’ that contains three data members: A template variable ‘data’, and a Node pointer ‘next’. You may define any member functions, if required, for this template class.
2.	Now using the above class, implement a Circular linked list Class named list, that supports the following operations:
a.	Insert at start:	 void insertAtStart(T const element)
b.	Insert v2 after V1:	 void insertAfter (T const v1,T const v2)
c.	Insert at End:          void insertAtStart(T const element)
d.	Delete from Start: void DeleteAtStart()
e.	DeleteAfter: void DeleteAfter(T const v1)
f.	Delete from End: void DeleteFromEnd()
g.	Print	 void print() const
h.	Is empty: bool isEmpty()
i.	Reverse a circular linked list: void reverse() 
j.	return iterator to first element: iterator begin() 
k.	return iterator to last element    iterator End()
l.	Destructor


3.	Now create a main function which has the following instructions:
a.	Define a Circular linked list object of type int.     
b.	Insert 7 and 9 at Start.
c.	Now insert 10, and 2 at end.
d.	Now print the linked list. (Sample answer:9->7>10->2)
e.	Insert 1 After 2.             
f.	Print the linked list.           (Sample answer:1->9->7>10-2)
g.	Now delete from start.
h.	Delete from end.
i.	Delete node after 10.
j.	Now print the linked list.   (Sample answer:7->10)
k.	Now reverse the Circular linked list.
l.	Now print the linked list.   (Sample answer:10->7)
m.	Now check if empty             (Sample answer: False)
n.	Insert 4  after 7 
o.	Print the list                        (Sample answer:4->10->7) 

