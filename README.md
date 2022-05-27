# Project-25_Mechanized-Chessboard
Chapter 4 code_Project_25 The second part 2 of "The Arduino World Book" code_Project_25  Mechanized Chessboard  
- code_Project_25
-  By:Farkad Adnan فرقد عدنان - 
 -E-mail: farkad.hpfa95@gmail.com 
-inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
- FaceBook: كتاب عالم الاردوينو 
- inst : arduinobook
1. #كتاب_عالم_الاردوينو
2. #كتاب_عالم_الآردوينو

* facebook : https://www.facebook.com/profile.php?id=100002145048612-
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/

 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>

# Mechanized-Chessboard
![istockphoto-961945932-612x612](https://user-images.githubusercontent.com/35774039/170603179-021a32d5-7318-4196-ad7f-71602757b251.jpg)
- غالبًا ما يذكر علماء النفس الشطرنج كطريقة فعالة لتحسين ذاكرتك. كما يتيح لك حل المشكلات المعقدة والتفكير في الأفكار. ليس من المستغرب أن الشطرنج أصبح موصى به في مكافحة مرض الزهايمر.
- يعتقد الكثير من الناس أن الشطرنج هي لعبة لمن هم أذكياء بطبيعتهم. هذا صحيح جزئيًا ، ولكن يمكنك أيضًا زيادة ذكائك بشكل كبير من خلال لعب الشطرنج. علاوة على ذلك ، أظهرت الدراسات أن الشطرنج ينشط نصفي الدماغ ، يحسن مهارات إبداعية، تركيز، التفكير النقديومهارات القراءة.

-Psychologists often mention chess as an effective way to improve your memory. It also allows you to solve complex problems and think of ideas. Not surprisingly, chess has become recommended in the fight against Alzheimer's disease.
Many people think that chess is a game for those who are naturally intelligent. This is partly true, but you can also significantly increase your intelligence by playing chess. Furthermore, studies have shown that chess activates both hemispheres of the brain, improving creative skills, concentration, critical thinking, and reading skills.
# الهيكل العام

![24](https://user-images.githubusercontent.com/35774039/170603395-ea3d7238-3b0f-48be-8f32-bc18419d6eb7.JPG)
![25](https://user-images.githubusercontent.com/35774039/170603400-90556b32-1ab4-46ca-b320-51d9d3acc4ec.JPG)

# الهيكل الداخلي للشطرنج
![26](https://user-images.githubusercontent.com/35774039/170603456-84a15cf0-0b5a-462a-b8bf-a7ba5f0afa6d.JPG)
# الادوات المستخدمة
```

XY table :

2 x V slot 20x20 linear rail, Length = 345 mm
1 x V slot 20x20 linear rail, Length = 315 mm
1 x V slot 20x20 linear rail, Length = 350 mm
1 x V slot 20x20 linear rail, Length = 395 mm
10 x 90 degree Corner Bracket
Transmission :

2 x GT2 Pulley, 20 teeth, 5mm bore
8 x GT2 Toothless pulley
3.5m x GT2 Belt
Electronics :

1 x Arduino Nano
2 x Stepper Motor - Adafruit - Nema 17 size - 200 steps/rev, 12V 350mA
2 x Stepper Motor Driver Carrier - Pololu - A4988
1 x LCD Module - I2C Serial - 2.6“
2 x Arcade button - Bore hole 23.5 mm
1 x Electromagnet - 5Kg Holding Force
1 x Freewheeling diode - 1N4001
1 x Power Transistor - TIP 120
2 x Micro Limit switch roller
64 x Reed Switch - Dia 2 x 14.5 mm
1 x Resistor - 1K ohm
4 x MUX breakout - SparkFun - CD74HC4067
1 x Terminal Block - DC Jack
Female Headers
10 x Screw Terminal
3 x Prototyping Board - 50 x 100 mm
4 x HE10 Connectors
8 x Ribbon Cable - 8
Chess :

1 x Chess pieces set - Staunton 3
1 x Chessboard Sticker - Squares size : 37 x 37 mm
32 x Magnet, Dia 8 x 3 mm
Box :

1 x Foamboard - 462 x 462 x 5 mm
1 x Foamboard - 462 x 462 x 10 mm
2 x Foamboard - 462 x 80 x 10 mm
2 x Foamboard - 442 x 80 x 10 mm
Bolting :

8 x Mini V Wheel
4 x Aluminium Spacer - ID : 5mm - Height : 6mm
4 x Eccentric Spacer - M5
4 x Hex. Locking Nut - M5
4 x Thin Hex. Nut - M5
8 x Mini Precision Shim - OD : 8 mm - ID : 5 mm - Thickness : 1 mm
26 x T-Nuts - M5
14 x Hex. Socket Button Head Cap Screw - M5 x 8 mm
12 x Hex. Socket Button Head Cap Screw - M5 x 12 mm
2 x Hex. Socket Button Head Cap Screw - M5 x 35 mm
2 x Hex. Socket Button Head Cap Screw - M5 x 30 mm
2 x Hex. Socket Button Head Cap Screw - M5 x 25 mm
8 x Hex. Socket Button Head Cap Screw - M5 x 15 mm
4 x Slotted Head Screw - M2 x 15 mm
4 x Nut - M2
8 x Hex. Socket Head Cap Screw - M3 x 10 mm
1 x Hex. Socket Head Cap Screw - M4 x 15 mm
4 x Slotted Countersunk Head Screw - M5 x 20 mm
4 x Nut - M5
```


# التصميم الثلاثي الابعاد للهيكل العام
# 3D design of the general structure
https://www.thingiverse.com/thing:5395942/files

# Core XY
![1_img14](https://user-images.githubusercontent.com/35774039/170605331-2bbf06c1-792f-4818-b1c6-6e0b5bbf9049.jpg)
![corexy-compare](https://user-images.githubusercontent.com/35774039/170605381-1d2aee46-94fa-494d-80fe-c5e5e3ec6923.jpg)


