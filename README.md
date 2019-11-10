# bmi
height = float(input("请输入您的身高（单位：米）:"))
weight = float(input("请输入您的体重（单位：千克）:"))
bmi = weight/height**2
if bmi <=18.5:
  print("您的体重偏瘦，请加强营养！")
elif 18.5<bmi<24.9:
  print("您的体重正常，请保持！")
elif 24.9<bmi<29.9:
  print("您的体重偏重，请加强运动！")
else:
  print("您的体重过重，请减肥！")
