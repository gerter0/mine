<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NATURE</title>
  <style>
    body {
  overflow-x: hidden;
}
.navigation-bar {
  z-index: 20;
  position: fixed; 
  top: 0; 
  right: 0; 
  background-color: #0dc84f; 
  padding: 10px; 
  border-radius: 10px;
}

.navigation-bar a {
 
  color: white; 
  text-decoration: none;
  padding: 8px 16px; 
  display: block; 
  border-radius: 10px;
}
.mountain img {
  width: 1649px; 
  height: 940px; 
  place-items: center;
  position: absolute;
  top: -80px;
  left: 50%;
  transform: translateX(-50%);
  mask-image: linear-gradient(to bottom, rgb(164, 219, 11) 80%, rgba(0, 0, 0, 0.003) 100%);
}

.LOGO {
  display: flex;
  justify-content: center;
  align-items: normal;
  height: 20em;
  position: relative;
  top: -4300px;
}

.treepantcount {
  z-index: 1;
  display: flex;
  justify-content: center;
  align-items: normal;
  height: 20em;
  position: relative;
  top: -2600px;
  font-size: 70px;
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
}

.blur {
  z-index: 2;
  position: absolute;
  top: -20%; /* Start the blur effect slightly above the shape */
  left: 0;
  width: 1480px;
  height: 1000px; /* Cover the top half and a bit more */
  background: rgb(164, 219, 11); /* Inherit the shape's background */
  filter: blur(50px); /* Apply blur effect */
  place-items: center;
  position: absolute;
  top: 740px;
  left: 50%;
  transform: translateX(-50%);
}

.squar {
  z-index: 3;
  position: flex;
  width: 3049px;
  height: 1300px; /* Cover the top half and a bit more */
  border-radius: 100%; /* This makes the element a circle */
  margin: 50px auto;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
  background: rgb(227, 234, 240); /* Inherit the shape's background */
  place-items: center;
  position: absolute;
  top: 700px;
  left: 50%;
  transform: translateX(-50%);
}
.squar2 {
  z-index: 5;
  position: flex;
  width: 3049px;
  height: 6300px; /* Cover the top half and a bit more */
  background: rgb(227, 234, 240); /* Inherit the shape's background */
  place-items: center;
  position: absolute;
  top: 2000px;
  left: 50%;
  transform: translateX(-50%);
}
.donation-box {
  z-index: 4;
  position: absolute;
  width: 350px;
  height: 500px; /* Cover the top half and a bit more */
  border-radius: 20px; /* This makes the element a circle */
  box-shadow: 10px 20px 5px rgba(0, 0, 0, 0.363);
  margin: auto;
  background: rgb(255, 244, 244);
  top: 700px;
  left: 50%;
  transform: translateX(-50%);
}
.contextdonation-box {
  position: relative;
  text-align: center;
  font-size:50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
}
.doantion-box-shape1 {
  position: relative;
  top:20px;
  left:10px;
  width: 150px;
  height: 50px;
  border-radius: 10px;
  background-color: rgb(12, 178, 70);
}
.doantion-box-shape2 {
  position: relative;
  z-index: 4;
  top:30px;
  left:10px;
  width: 150px;
  height: 50px;
  border-radius: 10px;
  background-color: rgb(12, 178, 70);
}
.doantion-box-shape3 {
  position: relative;
  z-index: 4;
  top:-80px;
  left:265px;
  transform: translate(-50%);
  width: 150px;
  height: 50px;
  border-radius: 10px;
  background-color: rgb(12, 178, 70);
}
.doantion-box-shape4 {
  position: relative;
  z-index: 4;
  top:-70px;
  left:190px;
  width: 150px;
  height: 50px;
  border-radius: 10px;
  background-color: rgb(12, 178, 70);
}
.doantion-box-shape5 {
  position: relative;
  z-index: 4;
  top: -50px;
  left:25px;
  width: 300px;
  height: 100px;
  border-radius: 10px;
  background-color: rgb(12, 178, 70);
}
.doantion-box-shape-text-mid {
  position: relative;
  text-align: center;
  top:30px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
}
.doantion-box-shape-text{
  position: relative;
  text-align: center;
  top:10px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
}
.donation-box-submit {
  position: relative;
  z-index: 4;
  top:-40px;
  left:80px;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(12, 178, 70);
}
.donation-box-submit-text {
  position: relative;
  text-align: center;
  top:20px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  color: rgb(0, 253, 0);
  font-size: 30px;
}
/* Leaf elements */
.leaf1, .leaf2, .leaf3, .leaf4, .leaf5, .leaf6, .leaf7, .leaf8, .leaf9, .leaf11 {
  z-index:3;
  scale: 60%;

  position: absolute;
}
 .leaf12, .leaf13, .leaf14, .leaf16, .leaf17, .leaf18, .leaf19, .leaf20 {
  z-index: 5;
  scale: 60%;
  top: 2700px;
  position: absolute;
}
.leaf21, .leaf22, .leaf23, .leaf24, .leaf25, .leaf26, .leaf27, .leaf28, .leaf28, .leaf29, .leaf29, .leaf30 {
  z-index: 5;
  position: absolute;
  top:5000px;
  
}
.leaderboard {
  z-index: 5  ;
  position: absolute;
  top: 1800px;
  left: 50%;
  transform: translateX(-50%);
  width: 800px;
  height: 1000px;
  border-radius: 20px;
  background-color: rgb(15, 209, 1);
}
.SignLeaderboard {
  position: absolute;
  z-index: 6;
  font-size: 130px;
  top:  1300px;
  left: 235px;
  font-family:'Franklin Gothic Medium', Arial, sans-serif;
  text-shadow:5px 10px rgb(10, 214, 34);
}
.About-us {
  position: relative;
  z-index: 8;
  display: flex;
  justify-content: center;
  align-items: normal;
  
  font-size: 70px;
  top:2700px;
  left:30px;
  font-size: 200px;
font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
text-shadow: 15px 15px rgb(106, 106, 106);
}
.About-us-content-container {
  z-index: 5;
  position: relative;
  
  top:2700px;
  left:75px;
  width: 1200px;
  height: 2000px;  
  background-color: rgba(255, 0, 0, 0);
}
.About-us-content-shape1{
  z-index: 6;
  position: absolute;
  top:40px;
  left:40px;
  width: 500px;
  height: 450px;  
  border-radius: 10px;
  background-image: linear-gradient(rgba(56, 215, 3, 0.616), rgb(0, 68, 7));
  
}
.About-us-content-shape-image1 {
  position: absolute;
  top: -230px;
  left: -350px;
  scale: 40%;
}
.About-us-content-shape-image1-text {
  position: absolute;
  top:330px;
  justify-content: center;
  text-align: center;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.About-us-content-shape2{
  z-index: 6;
  position: relative;
  top:40px;
  left:660px;
  width: 500px;
  height: 550px;  
  border-radius: 10px;
  background-image: linear-gradient(rgba(56, 215, 3, 0.616), rgb(0, 68, 7));
}
.About-us-content-shape-image2   {
  position: absolute;
  top: -590px;
  left: -780px;
  scale: 21%;
}

.About-us-content-shape-image2-text {
  position: absolute;
  top:330px;
  justify-content: center;
  text-align: center;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.About-us-content-shape3{
  z-index: 6;
  position: absolute;
  top:530px;
  left:40px;
  width: 500px;
  height: 550px;  
  border-radius: 10px;
  background-image: linear-gradient(rgba(226, 87, 87, 0.827), rgb(65, 1, 1));
}
.About-us-content-shape-image3  {
  position: relative;
  top: -200px;
  left: -250px;
  scale: 40%;
}

.About-us-content-shape-image3-text {
  position: absolute;
  top:330px;
  justify-content: center;
  text-align: center;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.About-us-content-shape4{
  z-index: 6;
  position: absolute;
  top:630px;
  left:600px;
  width: 500px;
  height: 550px;  
  border-radius: 10px;
  background-image: linear-gradient(rgba(172, 162, 162, 0.827), rgb(198, 188, 188));
}
.About-us-content-shape-image4 {
  position: relative;
  top: 10px;
  left: 120px;
  scale: 100%;
}

.About-us-content-shape-image4-text {
  position: absolute;
  top:330px;
  justify-content: center;
  text-align: center;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.About-us-content-shape5{
  z-index: 6;
  position: absolute;
  top:1200px;
  left:400px;
  width: 500px;
  height: 550px;  
  border-radius: 10px;
  background-image: linear-gradient(rgba(26, 166, 1, 0.827), rgb(6, 217, 24));
}
.About-us-content-shape-image5 {
  position: relative;
  top: 10px;
  left: 120px;
  scale: 100%;
}

.About-us-content-shape-image5-text {
  position: absolute;
  top:330px;
  justify-content: center;
  text-align: center;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.About-us-content-shape6 {
  z-index: 6;
  position: absolute;
  top:1200px;
  left:400px;
  width: 500px;
  height: 550px;  
  border-radius: 10px;
  background-color: rgb(11, 219, 156);
}
.About-us-content-shape-image6 {
  position: relative;
  top: 10px;
  left: 55px;
  scale: 100%;
  width:400px;
  height:200px;
}

.About-us-content-shape-image6-text {
  position: absolute;
  top:330px;
  justify-content: center;
  text-align: center;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.Onboard1 {
  position: relative;  
  left: 50%;
  top: 50px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard2 {
  position: relative;  
  left: 50%;
  top: 60px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard3 {
  position: relative;  
  left: 50%;
  top: 70px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard4 {
  position: relative;  
  left: 50%;
  top: 80px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard5 {
  position: relative;  
  left: 50%;
  top: 90px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard6 {
  position: relative;  
  left: 50%;
  top: 100px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard7 {
  position: relative;  
  left: 50%;
  top: 110px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Onboard8 {
  position: relative;  
  left: 50%;
  top: 120px;
  transform: translate(-50%);
  width: 700px;
  height: 100px;
  border-radius: 10px;
  background-color: rgba(119, 220, 110, 0.678);
}
.profile1 {
  display:inline-block;
  position: relative;
  top: 10px;
  left: 15px;
  width: 80px;
  height: 80px;
  border-radius: 100px;
  background-color: rgb(182, 189, 189);
}
.profileneckname1 {
  display: inline-block;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 30px;
  bottom: 20px;
  left: 30px;
}
.donated {
  position: relative;
  display: inline-block;
  width: 200px;
  height: 70px;
  border-radius: 10px;
  background-color: rgb(0, 255, 47)  ;
  bottom:20px;
  left:100px;
}
.Dcount {
  position: relative;
  display: inline-block;
  top: 5px;
  left: 60px;
  font-size: 50px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

/* Individual positions for each leaf */
.leaf1 {
  top: 900px;
  left: 35%;
  scale: 300%;
  filter: blur(2px);
  transform: translateX(-50%);
}

.leaf2 {
  top: 900px;
  left: 60%;
  transform: translateX(-50%);
}

.leaf3 {
  top: 1200px;
  left: 50%;
  transform: translateX(-50%);
}

.leaf4 {
  top: 1400px;
  left: 30%;
  transform: translateX(-50%);
}

.leaf5 {
  top: 1400px;
  left: 80%;
  transform: translateX(-50%);
}

.leaf6 {
  top: 1500px;
  left: 10%;
  transform: translateX(-50%);
}

.leaf7 {
  top: 1900px;
  left: 10%;
  transform: translateX(-50%);
}

.leaf8 {
  top: 1700px;
  left: 60%;
  transform: translateX(-50%);
}
.leaf9 {
  top: 1600px;
  left: 80%;
  rotate: 90deg;
  transform: translateX(-50%);
}

.leaf10 {
  top: 1000px;
  left: 10%;
  scale: 200%;
  transform: translateX(-50%);
}

.leaf11 {
  top: 900px;
  left: 60%;
  transform: translateX(-50%);
}
.leaf12 {
  top: 1200px;
  left: 50%;
  transform: translateX(-50%);
}
.leaf13 {
  z-index: 7;
  top: 2800px;
  left: 100%;
  transform: translateX(-50%);
  filter: blur(3px);
  scale: 500%;
}

.leaf14 {
  top: 2400px;
  left: 5 0%;
  transform: translateX(-50%);
}

.leaf15 {
  z-index:5;
  position: relative;
  top: -2100px;
  left:40%;
 filter: blur(4px);
  scale: 200%;
}

.leaf16 {
  top: 2000px;
  left: 30%;
  transform: translateX(-50%);
}

.leaf17 {
  top: 1900px;
  left: 1%;
  rotate: 190deg;
  transform: translateX(-50%);
}

.leaf18 {
  top: 2300px;
  left: 60%;
  transform: translateX(-50%);
}

.leaf19 {
  top: 1800px;
  left: 110%;
  transform: translateX(-50%);
  filter: blur(3px);
  scale: 250%;
}

/* Ensure images fit within their containers */
.leaf20 {
  max-width: 100%;
  max-height: 100%;
}
.leaf21 {
  
  left:40%;
  scale: 300%;
  filter: blur(2px);
  transform: translateX(-50%);
}

.leaf22 {
  z-index: 8;
  top:3400px;
  left: 80%;
  transform: translateX(-50%);
}

.leaf23 {
  top:3700px;
  left: 50%;
  transform: translateX(-50%);
}

.leaf24 {
  top:4000px;
  left: 10%;
  transform: translateX(-50%);
}

.leaf25 {
  top:4100px;
  left: 90%;
  transform: translateX(-50%);
}

.leaf26 {
  top:3000px;
  left: 50%;
  rotate: 40deg;
  transform: translateX(-50%);
}

.leaf27 {
  top:4500px;
  left: 10%;
  transform: translateX(-50%);
  scale: 200%;
  filter: blur(2px);
}

.leaf28 {
  top:4700px;
  left: 90%;
  transform: translateX(-50%);
}
.leaf29 {
  top:4700px;
  left: 40%;
  rotate: 90deg;
  transform: translateX(-50%);
}

.leaf30 {
  top: 5700px;
  left:90%;
  scale: 600%;
  filter: blur(2px);
  rotate: 100deg;
  transform: translateX(-50%);
}

.leaf31 {
  top: 900px;
  left: 60%;
  transform: translateX(-50%);
}
.leaf32 {
  top: 1200px;
  left: 50%;
  transform: translateX(-50%);
}
.leaf33 {
  z-index: 7;
  top: 2500px;
  left: 100%;
  transform: translateX(-50%);
  filter: blur(3px);
  scale: 500%;
}

.leaf34 {
  top: 2400px;
  left: 20%;
  transform: translateX(-50%);
}

.leaf35 {
  z-index:5;
  position: relative;
  top: 100px;
  left:40%;
 filter: blur(4px);
  scale: 200%;
}

.leaf36 {
  top: 2000px;
  left: 30%;
  transform: translateX(-50%);
}

.leaf37 {
  top: 1900px;
  left: 1%;
  rotate: 190deg;
  transform: translateX(-50%);
}

.leaf38 {
  top: 2300px;
  left: 60%;
  transform: translateX(-50%);
}

.leaf39 {
  top: 1800px;
  left: 110%;
  transform: translateX(-50%);
  filter: blur(3px);
  scale: 250%;
}

/* Ensure images fit within their containers */
.leaf40 {
  max-width: 100%;
  max-height: 100%;
}
.qwert {
  z-index: 5;
  scale: 80%;
  position: relative;
  top: -3100px;
  left: -290px;
}
.LOGO2 {
  z-index: 100;
  position: relative;
  top:-2685px;
  left: 250px;
}
.visit-us {
  z-index: 16;
  display: flex;
  justify-content: center;
  align-items: normal;
  height: 20em;
  position: relative;
  top: -2900px;
  font-size: 70px;
  font-size: 100px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.facebook {
  z-index: 101;
  position: relative;
  top: -4700px;
  left: 60px;
  scale: 35%;
}
.X {
  z-index: 101;
  position: relative;
  top: -5840px;
  left: -5px;
  scale: 4%;
}
.TikTok {
  z-index: 101;
  position: relative;
  top: -7000px;
  left: 340px;
  scale:35%;
}
.ytr{
  z-index:6;
  position: relative;
  top: 7130px;
  left: 390px;
  scale:300%;
}
  </style>
</head>
<body bgcolor="lightgreen">
  <div class="mountain">
    <img src="C:\Users\A_R_C\Desktop\website\pictue\AdobeStock_345267163_Preview.jpg"/>
  </div>
  
  <div class="blur"></div>
  <div class="squar"></div>
  <div class="squar2">
  </div>
  <div class="navigation-bar">
    <a href="#home" href="#section1">HOME</a>
    <a href="#about">ABOUT US</a>
    <a href="#LEADERBOARD">LEADERBOARD</a>
    <a href="#VISIT US">VISIT US</a>
  </div>
  <div><img src="C:\Users\A_R_C\Desktop\website\swwww.svg" class="ytr"></div>
  <div class="donation-box">
        <div class="contextdonation-box">JOIN #TEAMTREES!</div>
          <div class="doantion-box-shape1">
            <div class="doantion-box-shape-text">5 tress</div>
                </div>
                  <div class="doantion-box-shape2">
                    <div class="doantion-box-shape-text">10 tress</div>
                      </div>
                        
                          <div class="doantion-box-shape3">
                            <div class="doantion-box-shape-text">15 tress</div>
                              </div>
                                  <div class="doantion-box-shape4">
                                    <div class="doantion-box-shape-text">20 tress</div>
                                      </div>
                                          <div class="doantion-box-shape5">
                                            <div class="doantion-box-shape-text-mid">50 tress</div>
                                             </div>
                                                  <div class="donation-box-submit"><p class="donation-box-submit-text">DONATE</p></div>
                                              </div>                                      
<div class="About-us">
  <section id="about" ></section><p>ABOUT US</p>
</div>
  <div class="About-us-content-container">
    <div class="About-us-content-shape1"><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\Planting trees.webp" class="About-us-content-shape-image1" alt=""><p class="About-us-content-shape-image1-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, praesentium! Voluptatibus recusandae fuga at distinctio consequatur ducimus culpa. Totam debitis officiis dolore temporibus obcaecati labore maiores consequatur dolorum odit eos.</p></div>
    <div class="About-us-content-shape2"><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\(2)+Uganda_FED_2012.jpg" class="About-us-content-shape-image2" alt=""><p class="About-us-content-shape-image1-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, praesentium! Voluptatibus recusandae fuga at distinctio consequatur ducimus culpa. Totam debitis officiis dolore temporibus obcaecati labore maiores consequatur dolorum odit eos.</p></div>
    <div class="About-us-content-shape3"><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\wildfire_biscuitWEB.jpg" class="About-us-content-shape-image3" alt=""><p class="About-us-content-shape-image1-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, praesentium! Voluptatibus recusandae fuga at distinctio consequatur ducimus culpa. Totam debitis officiis dolore temporibus obcaecati labore maiores consequatur dolorum odit eos.</p></div>
    <div class="About-us-content-shape4"><img src="C:\Users\A_R_C\Desktop\website\pictue\258px-Kiloware.jpg" class="About-us-content-shape-image4" alt=""><p class="About-us-content-shape-image1-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, praesentium! Voluptatibus recusandae fuga at distinctio consequatur ducimus culpa. Totam debitis officiis dolore temporibus obcaecati labore maiores consequatur dolorum odit eos.</p></div>
  
    <div class="About-us-content-shape6"><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\96a1-tree-planting-stewardship-events-banner.png" class="About-us-content-shape-image6" width="400" height="300" alt=""><p class="About-us-content-shape-image1-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, praesentium! Voluptatibus recusandae fuga at distinctio consequatur ducimus culpa. Totam debitis officiis dolore temporibus obcaecati labore maiores consequatur dolorum odit eos.</p></div>
  </div>
  <div class=""></div>
  <div class="SignLeaderboard">
    <section id="LEADERBOARD" ></section><p>LEADERBOARD</p>
  </div>
  <div class="leaderboard">
    <div class="Onboard1">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard2">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard3">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard4">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard5">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard6">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard7">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
          </div>
    </div>
    <div class="Onboard8">
      <div class=profile1></div>
        <div class="profileneckname1">USER169857</div>
          <div class="donated">
            <div class="Dcount">594</div>
</div>
    </div>
    </div>
  <div class="treepantcount">
    <section id="home" ></section> <p>14,654,871,651</p>
   
   
  </div>
  <div class="LOGO">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pngwing.com.png"/>
  </div>

  
  <!-- Leaf elements -->
  <div class="leaf1">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 1">
  </div>
  <div class="leaf2">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 2">
  </div>
  <div class="leaf3">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 3">
  </div>
  <div class="leaf4">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 4">
  </div>
  <div class="leaf5">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 5">
  </div>
  <div class="leaf6">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 6">
  </div>
  <div class="leaf7">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 7">
  </div>
  <div class="leaf8">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 8">
  </div>
  <div class="leaf9">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 9">
  </div>
  <div class="leaf10">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 1">
  </div>
  <div class="leaf11">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 2">
  </div>
  <div class="leaf12">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 3">
  </div>
  <div class="leaf13">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 4">
  </div>
  <div class="leaf14">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 5">
  </div>
  <div class="leaf15">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 6">
  </div>
  <div class="leaf16">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 7">
  </div>
  <div class="leaf17">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 8">
  </div>
  <div class="leaf18">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 9">
  </div>
  <div class="leaf19">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 9">
  </div>
  <div class="leaf20">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 9">
  </div>
  <div class="leaf21">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 1">
  </div>
  <div class="leaf22">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 2">
  </div>
  <div class="leaf23">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 3">
  </div>
  <div class="leaf24">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 4">
  </div>
  <div class="leaf25">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 5">
  </div>
  <div class="leaf26">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 6">
  </div>
  <div class="leaf27">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 7">
  </div>
  <div class="leaf28">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 8">
  </div>
  <div class="leaf29">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 9">
  </div>
  <div class="leaf30">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 1">
  </div>
  <div class="leaf31">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 2">
  </div>
  <div class="leaf32">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 3">
  </div>
  <div class="leaf33">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-1.png" alt="Leaf 4">
  </div>
  <div class="leaf34">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-2.png" alt="Leaf 5">
  </div>
  <div class="leaf35">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 6">
  </div>
  <div class="leaf36">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 7">
  </div>
  <div class="leaf37">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 8">
  </div>
  <div class="leaf38">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 9">
  </div>
  <div class="leaf39">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-3.png" alt="Leaf 9">
  </div>
  <div class="leaf40">
    <img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\Untitled-4.png" alt="Leaf 9">
  </div>
<div class="LOGO2"><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pngwing.com.png"></div>
  <div><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\Untitled-1.svg" class="qwert">  
</div>  
<div class="visit-us">
  <section id="VISIT US" ></section> VISIT US</p>
</div>
<div class=facebook><a href="https://x.com/?lang=en" target=_blank><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\images (1)s.png"></a></div>
<div class=X><a href="https://facebook.com/?lang=en" target=_blank ><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\Facebook_icon_(black).svg (1).png"></a></div>
<div class=TikTok><a href="https://www.tiktok.com/en/" target=_blank ><img src="C:\Users\A_R_C\Desktop\website nature\NATURE\img\pictue\4138151.png"></a></div>
</body>
</html>
