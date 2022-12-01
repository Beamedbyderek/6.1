# 6.1
public static void main(String[] args) {
    int input = 25; //this is whatever value you're going up to.
    int accumulator = 0; //keep track of the total sum
    for (int i = 0; i < input; i++) {
        if (i % 2 == 1) { //if odd
            accumulator+=i; // add to the running total sum
        }
    }
    System.out.println(accumulator/(input/2)); //print out the total/num of numbers
}
