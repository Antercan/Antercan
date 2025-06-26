class MahmoudAnter:
    def __init__(self):
        self.name = "Mahmoud Anter"
        self.profession = "Fachinformatiker in Ausbildung (Anwendungsentwicklung)"
        self.skills = ["Python", "SQL", "HTML", "CSS", "Git", "VSCode"]
        self.languages = {
            "Arabic": "C1",
            "German": "C1",
            "English": "C1",
            "Kurdish-Kurmanji": "C1",
            "Kurdish-Sorani": "B2",
            "Turkish": "B2"
        }
        self.experience = ["Gastro-Konsultant", "Selbstständig", "IT-begeistert"]
        self.learning = ["OOP", "APIs", "SQL Joins", "Fehlersuche", "Projektarbeit"]
        self.goals = ["Softwareentwicklung", "eigenes Tech-Business", "-Digitalisierung"]
    
    def say_hi(self):
        return "Hi, ich bin Mahmoud – let's build something great together! 🚀"

me = MahmoudAnter()
print(me.say_hi())
