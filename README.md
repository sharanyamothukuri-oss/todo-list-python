tasks = []

def add_task(task):
    tasks.append(task)


add_task("Learn Git")
add_task("Practice Python")
add_task("Build projects")


print("My Todo List:")

for task in tasks:
    print("-", task)
