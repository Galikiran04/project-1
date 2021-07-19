# project-1
{
  box-sizing: border-box;
}

body{
  margin: 0px;
  padding: 0px;
  font: poppins;
}

#main{
  width:100%;
  height: 45vh;
  position: relative;
}

nav{
  display: flex;
  justify-content: space-around;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: white;
  box-shadow: 5px 10px 30px rgba(0, 0, 0, 0.02);
  z-index: 1;
  }

.logo img{
  height:45px;
}

.menu{
  list-style: none;
  display: flex;
}
.menu li a{
  height: 40px;
  line-height: 43px;
  margin: 3px;
  padding: 0px 22px;
  display: flex;
  font-size: 0.8em;
  text-transform: uppercase ;
  font-weight: 500;
  letter-spacing: 1px;
  color: gray;
}

a{
  text-decoration: none;
}
.hey{
  color: #39bfbd;
  font-weight: 500;
  font-size: 0.9em;
  border-bottom: 2px solid #39bfbd;
}

.image{
  width: 500px;
  height:500px;
}
.image img{
  width: 120%;
  height:120%;
  object-fit:contain;
  
}

.content{
  display: flex;
  width: 100%;
  justify-content: space-around;
  align-items:center;
  position: relative;
  left: 50%;
  right:50%;
  transform: translate(-50%,-50%)
  
}

.main-text {
  width: 500px;
}
.main-text h1 {
  font-size: 3.5em;
  color: #1c3548;
  margin: 0px 10px 0px;
  line-height: 60px;
}

.main-text p {
  color: gray;
}

.resume-btn{
  width: 190px;
  height:44px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  background-color: #1bd096;
  border-radius: 20px;
  box-shadow: 5px 10px 30px rgba(24,139,119,0.2);
}

.resume-btn:hover {
  background-color: #23cdaf;
  transition: all ease 0.2s;
}

.menu li a:hover{
  background-color: #23cdaf;
  color: white;
  box-shadow: 5px 10px 30px rgba(24,139,119,0.2);
  transition: all ease 0.2s;
}
