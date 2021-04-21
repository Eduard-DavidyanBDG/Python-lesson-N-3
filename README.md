# Python-lesson-N-3
Functions
        "Das-3"
                "N-1"
                    def polindrom_find(name):
                        if name[0::] == name[::-1]:
                            print(True)
                        else:
                            print(False)
                    polindrom_find(str(input()))



                "N-2"
                    def hashvich(pi, r):
                        S = pi * r**2
                        print(S)
                    hashvich(3.14, int(input()))

                "N-3"
                    def show_employee_basic_data(name, age):
                        print(name, age)
                    show_employee_basic_data("Eduard", 16)

                "N-4"-----??????




                "N-5"
                    def show_employee_basic_data(name, age):
                        print(name, age)
                    show_employee_basic_data("Eduard", 16)




                    def kanchum():
                        kanch = show_employee_basic_data
                        return kanch
                        print(kanch)
                    kanchum()
