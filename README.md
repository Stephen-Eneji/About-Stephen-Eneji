def __init__(self, personalInfo, skills, projects):
    self.personalInfo = personalInfo
    self.skills = skills
    self.projects = projects

#Personal Infomation
def personalInfo():
    personalInfo = ("name: Stephen Eneji",
                        " >Education: B.Sc. Computer Science (2021 - 2025",
                        " >Email: enejistephen01@gmail.com",
                        " >GitHub: https://github.com/Stephen-Eneji",
                        " >LinkedIn: https://www.linkedin.com/in/stephen-eneji-382471209/",
                        " >Whatsapp: +2348166668759",
                        " >Instagram/twitter: @heiseneji")
    print(personalInfo)

personalInfo()

#Skills
def skills():
    ski1 = "skillsSoFar: 'HTML', 'CSS', 'BootStrap', 'JavaScript' +ES6, 'Python'",
    ski2 = "troubleShoot.Resources: "'Google', 'Stackoverflow', 'Twitter', 'Dev Circle',
    ski3 = "'Git', 'GitHub', 'Version Control'"
    print(ski1)
    print(ski2)
    print(ski3)

skills()

#Projects so far (To be updated with time)
def projects():
    prj = {1: "Matrispy =  Matrix calculator to solve any type of logic for any type of Matrix",
                2: "toDoApp =  Work in progress",
                3: "Built.Multiple.Websites.freelancing =  Cyberinfomatic.com, greentech.com.ng"}
    print(prj[1])
    print(prj[2])
    print(prj[3])

projects()

