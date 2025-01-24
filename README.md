# Get the dimensions of the matrix
rows = int(input("Enter the number of rows: "))
cols = int(input("Enter the number of columns: "))

# Initialize an empty matrix
matrix = []

# Get the elements of the matrix from the user
print("Enter the elements row by row:")
for i in range(rows):
    row = []
    for j in range(cols):
        element = int(input(f"Enter element for row {i+1}, column {j+1}: "))
        row.append(element)
    matrix.append(row)

# Print the matrix
print("\nThe matrix is:")
for row in matrix:
    print(row)
