# ZuriLearn
def find_anagram():
    string1 = input('Enter first word ')
    string2 = input('Enter second word ')
    if sorted(string1) == sorted(string2):
        print('True')
    else:
        print('false')
find_anagram()
