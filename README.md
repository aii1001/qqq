# qqq
class AttestationResult:
    def __init__(self, student, semester, subjects, grades):
        self.student = student
        self.semester = semester
        self.subjects = subjects
        self.grades = grades
res1 = AttestationResult("Иванов Иван", 1, ["Математика", "Физика"], ["Отлично", "Хорошо"])
res2 = AttestationResult("Петрова Анна", 2, ["Биология", "История"], ["Хорошо", "Отлично"])
print(res1.student, res1.semester, res1.subjects, res1.grades)
print(res2.student, res2.semester, res2.subjects, res2.grades)
