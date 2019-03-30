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


สรุป ความสัมพันธ์ระหว่าง CPI (ดัชนีผู้บริโภค) และ ค่าแรงขึ้นต่ำมีค่า accuracy สูงที่สุดในกรุงเทพ 90.14% รองลงมาคือภาคใต้ 86.42 %



พรรคพลังประชารัฐ
400-425 บาท/วัน >> CPI จะได้ 110-112 ตามลำดับ ความหมายคร่าวๆ คือ กทม. ข้าวของจะแพงขึ้น 10-12% 

พรรคเพื่อไทย
400 บาท/วัน >> CPI จะได้ 110 ความหมายคร่าวๆ คือ กทม. ข้าวของจะแพงขึ้น 10% 

พรรคประชาธิปัตย์
400 บาท/วัน >> CPI จะได้ 110  ความหมายคร่าวๆ คือ กทม. ข้าวของจะแพงขึ้น 10% 

พรรคอนาคตใหม่
450 บาท/วัน >> CPI จะได้ 115 ความหมายคร่าวๆ คือ กทม. ข้าวของจะแพงขึ้น 15% 

พรรคสามัญชน 
500 บาท/วัน >> CPI จะได้ 120.44 ความหมายคร่าวๆ คือ กทม. ข้าวของจะแพงขึ้น 20.44% 

พรรคประชานิยม 
360 บาท/วัน CPI จะได้ 105.93 ความหมายคร่าวๆ คือ กทม. ข้าวของจะแพงขึ้น 5.93% 


*ทั้งนี้อาจมีรายละเอียดย่อย เช่น ระดับการศึกษา, การประกันค่าจ้าง, กลุ่มคนแรงงานฝีมืออาชีพ, กรอบระยะเวลาที่ดำเนินนโยบาย และอื่นๆ  [อ้างอิง]( https://www.msn.com/th-th/news/thailand-election-2019/%E0%B9%80%E0%B8%9B%E0%B8%A3%E0%B8%B5%E0%B8%A2%E0%B8%9A%E0%B9%80%E0%B8%97%E0%B8%B5%E0%B8%A2%E0%B8%9A%E0%B8%8A%E0%B8%B1%E0%B8%94%E0%B9%86-%E2%80%9C%E0%B8%99%E0%B9%82%E0%B8%A2%E0%B8%9A%E0%B8%B2%E0%B8%A2%E0%B8%84%E0%B9%88%E0%B8%B2%E0%B9%81%E0%B8%A3%E0%B8%87%E0%B8%82%E0%B8%B1%E0%B9%89%E0%B8%99%E0%B8%95%E0%B9%88%E0%B8%B3%E2%80%9D-6-%E0%B8%9E%E0%B8%A3%E0%B8%A3%E0%B8%84%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%A1%E0%B8%B7%E0%B8%AD%E0%B8%87-%E0%B8%A8%E0%B8%B6%E0%B8%81%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%8762/ar-BBUNEGQ)


 
