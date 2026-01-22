def save_note():
note = input("Enter note:")
"a")

file.close()
print("Note saved successfully")
def read_notes():
try:

print("Saved Notes:")
print(file.read())
file.close()
except:
print("No notes found")
def main():
while True:
print("1. Save Note")
print("2. Read Notes")
print("3. Exit")
choice= input("Choose option:")
if choice=="1":
save_note()
elif choice =="2":
read_notes()
elif choice=="3":
break
else:
print("Invalid option")
main()
