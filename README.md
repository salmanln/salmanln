```python
def count_characters(text):
    """
    Count the number of characters in a given text.
    """
    return len(text)

if __name__ == "__main__":
    user_input = input("Enter some text: ")
    count = count_characters(user_input)
    print(f"The text has {count} characters.")
```
