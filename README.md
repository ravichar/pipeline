class SoftwareDeveloper:
    def __init__(self):
        self.name = "Ravi Char"
        self.languages = ["Python", "Java", "C"]
        self.tools = ["Git", "IDEA", "Metasploit"]
        self.interests = ["Software Development", "Cybersecurity", "Cloud", "AI"]
        self.hobby = ["Bansuri", "Roller Skating"]

    def greet(self):
        print("Hi there! 👋 I'm Ravi Char, a Software Developer.")
        print("I'm passionate about being useful - coding, Cybersecurity:")
        print(f"- Languages: {', '.join(self.languages)}")
        print(f"- Tools: {', '.join(self.tools)}")
        print(f"- Interests: {', '.join(self.interests)}")

# Create an instance of the SoftwareDeveloper class
developer = SoftwareDeveloper()

# Call the greet method
developer.greet()
