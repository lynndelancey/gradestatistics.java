# gradestatistics.java
START
    INITIALIZE an array to store 10 floating-point grades
    PROMPT user to enter 10 grades
    READ the grades into the array using a for-loop

    CALCULATE total as the sum of grades
    CALCULATE average as total divided by 10
    INITIALIZE max as the first grade
    INITIALIZE min as the first grade

    FOR each grade in the array
        IF grade is greater than max
            SET max to grade
        IF grade is less than min
            SET min to grade
    END FOR

    DISPLAY average
    DISPLAY max
    DISPLAY min
END

