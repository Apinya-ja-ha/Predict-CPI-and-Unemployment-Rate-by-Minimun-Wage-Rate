# Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate
คาดการดัชนีผู้บริโภค และ อัตราการว่างงาน จากค่าจ้างขั้นต่ำ

Objective : คือศึกษาความสัมพันธ์ของการขึ้นค่าจ้างขึ้นต่ำจากนโยบายพรรคการเมืองต่างๆ
          และคาดการณ์ อัตราการว่างงาน(Unemployment rate) และ ดัชนีผู้บริโภค(CPI)ได้เมื่อทราบค่าแรงขั้นต่ำ (Minimun wage rate)

ขอบเขตและแนวทางการศึกษา : คาดการณ์โดยใช้ Linear regression
                         พิจารณาเป็นรายไตรมาสตั้งแต่ปี 2550-2561 (12ปี)
                         พิจารณาเป็นรายภาค โดยหาค่าเฉลี่ยจากจังหวัดต่างๆ ในแต่ละภาค ได้แบ่ง 6 ภาคเป็น กรุงเทพ/ปริมณฑล/ใต้/เหนือ/ตะวันออกเฉียงเหนือ/กลาง*รวม                          กทม. และปริมณฑล
                         
1.ความสัมพันธ์ระหว่าง อัตราการว่างงานและค่าแรงขั้นต่ำ

กรุงเทพ :
[Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/Unempolyment-and-Minimum-wage-rate/UnemMWRBKK.ipynb](https://github.com/Apinya-ja-ha/Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/blob/master/Unempolyment-and-Minimum-wage-rate/UnemMWRBKK.ipynb)
      
ปริมณฑล :
[Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/Unempolyment-and-Minimum-wage-rate/UnemMWRVi.ipynb](https://github.com/Apinya-ja-ha/Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/blob/master/Unempolyment-and-Minimum-wage-rate/UnemMWRVi.ipynb)

ภาคใต้ :
[Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/Unempolyment-and-Minimum-wage-rate/UnemMWRSouth.ipynb](https://github.com/Apinya-ja-ha/Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/blob/master/Unempolyment-and-Minimum-wage-rate/UnemMWRSouth.ipynb)

ภาคเหนือ :
[Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/Unempolyment-and-Minimum-wage-rate/UnemMWRNorth.ipynb](https://github.com/Apinya-ja-ha/Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/blob/master/Unempolyment-and-Minimum-wage-rate/UnemMWRNorth.ipynb)

ภาคตะวันออกเฉียงเหนือ :
[Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/Unempolyment-and-Minimum-wage-rate/UnemMWRNE.ipynb](https://github.com/Apinya-ja-ha/Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/blob/master/Unempolyment-and-Minimum-wage-rate/UnemMWRNE.ipynb)

ภาคกลาง : 
        [Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/Unempolyment-and-Minimum-wage-rate/UnemMWRCT.ipynb](https://github.com/Apinya-ja-ha/Predict-CPI-and-Unemployment-Rate-by-Minimun-Wage-Rate/blob/master/Unempolyment-and-Minimum-wage-rate/UnemMWRCT.ipynb)

 สรุป
 เมื่อดูจาก กราฟ scatter พบว่าแทบไม่มีความสัมพันธ์กันระว่าง ค่าจ้างขั้นต่ำและอัตราการว่างงาน 
 นั่นคือเมื่อใช้การทำนายจาก regression model พบว่า มีค่า accuracy มากที่สุดเพียง 31.82% คือกรุงเทพ และต่ำสุด 6.33% คือกลุ่มจังหวัดปริมณฑล
 ทั้งนี้ทำให้การใช้ model ดังกล่าวในการทำนาย อัตราการว่างงาน มีความไม่แม่นยำสูงไม่ว่าจะในภาคไหนก็ตาม
 
 
2.ความสัมพันธ์ระหว่าง CPIและค่าแรงขั้นต่ำ

กรุงเทพ : [CPI-and-Minimum-wage-rate/CPI-and-Minimum-wage-rate/CPIMWRBKK.ipynb](https://github.com/Apinya-ja-ha/CPI-and-Minimum-wage-rate/blob/master/CPI-and-Minimum-wage-rate/CPIMWRBKK.ipynb)

ปริมณฑล :
[CPI-and-Minimum-wage-rate/CPI-and-Minimum-wage-rate/CPIMWRVi.ipynb](https://github.com/Apinya-ja-ha/CPI-and-Minimum-wage-rate/blob/master/CPI-and-Minimum-wage-rate/CPIMWRVi.ipynb)

ภาคใต้ :
[CPI-and-Minimum-wage-rate/CPI-and-Minimum-wage-rate/CPIMWRSouth.ipynb](https://github.com/Apinya-ja-ha/CPI-and-Minimum-wage-rate/blob/master/CPI-and-Minimum-wage-rate/CPIMWRSouth.ipynb)

ภาคเหนือ :
[CPI-and-Minimum-wage-rate/CPI-and-Minimum-wage-rate/CPIMWRNorth.ipynb](https://github.com/Apinya-ja-ha/CPI-and-Minimum-wage-rate/blob/master/CPI-and-Minimum-wage-rate/CPIMWRNorth.ipynb)

ภาคตะวันออกเฉียงเหนือ :
[CPI-and-Minimum-wage-rate/CPI-and-Minimum-wage-rate/CPIMWRNE.ipynb](https://github.com/Apinya-ja-ha/CPI-and-Minimum-wage-rate/blob/master/CPI-and-Minimum-wage-rate/CPIMWRNE.ipynb)

ภาคกลาง : 
[CPI-and-Minimum-wage-rate/CPI-and-Minimum-wage-rate/CPIMWRCT.ipynb](https://github.com/Apinya-ja-ha/CPI-and-Minimum-wage-rate/blob/master/CPI-and-Minimum-wage-rate/CPIMWRCT.ipynb)




 
