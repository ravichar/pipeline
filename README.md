```
class SoftwareDeveloper:
    def __init__(self):
        self.name = "Ravi Char"
        self.languages = ["Python"]
        self.tools = ["Git", "Jupyter", "Visual Studio"]
        self.interests = ["Machine Learning", "Algorithms", "Data Structures"]

    def greet(self):
        print("Hi there! 👋 I'm Ravi Char, a Software Developer.")
        print("I'm passionate about coding and here are some of my details:")
        print(f"- Languages: {', '.join(self.languages)}")
        print(f"- Tools: {', '.join(self.tools)}")
        print(f"- Interests: {', '.join(self.interests)}")

# Create an instance of the SoftwareDeveloper class
developer = SoftwareDeveloper()

# Call the greet method
developer.greet()
```
