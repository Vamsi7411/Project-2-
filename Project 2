def count_words(text):
    word_count=len(text.split())
    return word_count
def main():
    while True:
        text=input("write the sentence to count ('or quit to exit): ")
        if text.lower()=='quit':
            break
        if not text:
            print("enter some text to count")
            continue
        word_count=count_words(text)
        print("the word count is",word_count)
if __name__=="__main__":
    main()
