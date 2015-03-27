#TGIF
##Things I like to do on Friday

*Stare at my watch
*Eat tacos
	* Beef
	* And chicken
	* Not fish
*Beer
	*More beer

####Friday Schedule
1. Pass out **at work**
2. Wake up
3. Get **_TACOS_** for _lunch_
4. Try to leave work early
	*_Without my boss noticing_

for(int i=0; i < 10; i++) {
	int counter;
	for (int y=10;y<=100;y--) {
	counter++;
	}
}
void printGrid(int gameArray[][20], int gridSize) {
		/*invoked in:
		* createArray()
		* checkForMine()
		* */
		//print the array out as a grid to play on. format so evenly spaced
		//need to pass the array, and if you want its size so it can print it out row by row.
		//Then after each turn you can invoke this to reprint the newly updated grid.
		int borderX[20];
		int borderY[20];
		for (int i = 0; i < gridSize; i++) {                                                                                                                           //print border/x-axis...numbers across the top.
			if (i == 0) {
				cout << "  ";
			}
			borderX[i] = (i + 1);
			cout << setw(3) << borderX[i];
		}
		cout << setw(2) << endl;
		for (int row = 0; row < gridSize; row++) {
			borderY[row] = row + 1;
			cout << (row + 1);
			for (int column = 0; column < gridSize; column++) {
				cout << setw(3) << gameArray[row][column] << setw(2);
			}
			cout << endl;
		}
	}

[go here if you wanna look like you're a super hacker](http://hackertyper.com)

