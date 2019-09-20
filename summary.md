Summary
-
StringTest
-
    [1] should_be_immutable
    
    [2] all_modification_method_will_create_new_string
    
    [3] will_create_new_string_when_concat
    
    [4] should_taken_string_apart
    
    [5] should_taken_string_apart_continued
    
    [6] should_break_string_into_words
    
    [7] should_break_string_into_words_customized
    
    [8] should_create_ascii_art
    
    [9] should_calculate_checksum_of_a_string
    
    [10] should_convert_unicode_escape
    
    [11] should_reverse_a_string
    
    [12] should_compare_string_with_different_cases
    
    [13] should_format_string

    Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
    
    A1: To know more about string equalities and to learn more about and the usage of common string functions.

    Q2: Why the test failed at first?
    
    A2: Because the expected values are not set.

    Q3: Why you corrected the test that way?
    
    A3: Test [1-3] Added false results as they all are not equal strings due to the other one being modified.
    Test [4-5] Used substring to get part of the string, passed the starting and ending indices of the part I needed.
    - What if the input arguments is out of range of the string = StringIndexOutOfBoundsException
    - What will happen if the the starting index is greater than the ending index = StringIndexOutOfBoundsException
    - What will happen if the input string is of null reference = NullPointerException
    Test [6-7] Used string split and passed in the delimiter I wanted to get the list of words I needed.
    Test [8] Used append function of string builder to create the word art.
    Test [9] Looped on the character value of each letter and added its integer value to the sum.
    Test [10] Formatted it to a string by using \u and using the code to get the characters i needed.
    Test [11] Used StringBuilder's existing function named reverse.
    Test [12] Added false to the 1st result as the condition is case sensitive, but true on the 2nd result as it ignores the cases.
    Test [13] Added the expected string as String.format pushes the values of the variables to the string.

    Q4: Do you have further questions on this knowledge point?
    
    A4: None
