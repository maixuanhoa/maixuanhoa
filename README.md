#bài 1:
my_list = [0, 1, 4, 'g', 6]
print(my_list[0])
print(my_list[1])
print(my_list[-2])
print(my_list[-1])
#bài 2
m_list = [0, 2, 4, 5, 1]
max_list = m_list[0]
for i in range(len(m_list)):
    if m_list[i] > max_list:
        max_list = m_list[i]
print(f"max = {max_list}")

min_list = m_list[0]
for i in range(len(m_list)):
    if m_list[i] < min_list:
        min_list = m_list[i]
print(f"min = {min_list}")
#bài 3
baby_list = [0, 1, 2, 3, 4, 5]
baby_list.append(6)
print(baby_list)
#bài 7
house = ["pan", "sofa", "hammer", "pilow"]
print("pan" in house)
print("pilow" not in house)

các bài khác em không biết làm kiểu gì ạ.a có thể gợi ý cho e được không ạ.e cám ơn a 
