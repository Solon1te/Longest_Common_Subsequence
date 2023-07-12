Longest Common Subsequence

The longest_common_subsequence() function finds the longest common subsequence between two strings using dynamic programming. It calculates the length of the longest common subsequence and returns the subsequence itself.
Function Signature

def longest_common_subsequence(string_1, string_2):
    """
    Finds the longest common subsequence between two strings.

    Args:
        string_1 (str): The first input string.
        string_2 (str): The second input string.

    Returns:
        str: The longest common subsequence.

    """

Usage Example

dna_1 ='ACCGTT'
dna_2 ='CCAGCA'     

print(longest_common_subsequence(dna_1, dna_2))

What I Learned

Working with the longest_common_subsequence() function provided an opportunity to learn 2 key concepts:

    Dynamic programming: The function uses a dynamic programming approach to solve the longest common subsequence problem efficiently by breaking it down into smaller subproblems and storing their solutions in a grid.

    Grid construction: The function constructs a grid to store the lengths of the common subsequences for various prefixes of the input strings.

By working with this function, I gained hands-on experience with dynamic programming and learned how to find the longest common subsequence between two strings efficiently.
