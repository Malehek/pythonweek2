# pythonweek2
#creating an empty list name my_list.
my_list = []
#appending items into the list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
#creating another list
another_list = [50, 60, 70]
#extending my list
my_list.extend(another_list) 
#removing the last element
my_list.pop()
#sorting the list
my_list.sort()
#find and printing the value of thirty
item = 30
index = my_list.index(item)
print(f"the index of {item} is: {index})