def count_specific_letter(text, lette):
    return text.lower().count(letter.lower())

if __name__ == "__main__":
    sample = "GitHub Daily Commit"
    letter = "i"
    print(f"The letter '{letter}' appears {count_specific_letter(sample, letter)} times.")
