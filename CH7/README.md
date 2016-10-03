# Data Structure Note CH7

## Result
```shell
> javac C07_List.java
> java C07_List
=== Array List ===
Round 1: normally insert items
[1, 3, 2]
Round 2: size of the stored array exceeded
[4, 1, 3, 2, 0, 0]
=== Linked List ===
[9, 8, 7]
```
## Instruction
### C07_List.java
Including two kinds of List, there are array list and linked list.

Class ArrayList implement the array list.
```java
class ArrayList {
	private int stored[];
	private int lastIndex;
	public ArrayList() { ... }
  public void insertItem(int newItem, int location) { ... }
	public void printList() { ... }
}
```