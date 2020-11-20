class Solution:
    def detectCapitalUse(self, word: str) -> bool:
        if word.isupper():
            return 1
        if word.islower():
            return 1
        if word[0].upper() and word[1:].islower():
            return 1
        return 0
