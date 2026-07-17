# python-assignment-
# Open a file named "sample.txt" in write mode
# This creates the file if it does not already exist
with open("sample.txt", "w") as file:
    # Write some text into the file
    file.write("Hello, this is a sample text file.\n")
    file.write("Python file handling is easy to learn.\n")

# Open the same file in read mode
with open("sample.txt", "r") as file:
    # Read all content from the file
    content = file.read()

# Display the content on the screen
print("File content:")
print(content)
