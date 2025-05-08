numbers = [12, 7, 5, 8, 15, 22, 3, 10]
2_defe_artan_cut_eded = [num * 2 for num in numbers if num % 2 == 0]
with open("cut_ededler.txt", "w") as file:
    for num in 2_defe_artan_cut_eded:
        file.write(str(num) + "\n")

if 2_defe_artan_cut_eded:
    average = sum(2_defe_artan_cut_eded) / len(2_defe_artan_cut_eded)
    print("Cüt ədədlərin 2 dəfə artırılmışlarının ədədi ortası:", average)
else:
    print("Cüt ədəd tapılmadı.")
