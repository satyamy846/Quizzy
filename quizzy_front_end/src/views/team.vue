<template>

<div class="team section" id="team">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 col-md-6">
          <div class="team-member">
            <div class="main-content">
              <img src="../assests/images/member1.png" alt="member1">
              <span class="category">SDE @Optum</span>
              <h4>Shivam Yadav</h4>
              <ul class="social-icons">
                <li><a href="#"><i class="fab fa-facebook"></i></a></li>
                <li><a href="https://github.com/Shivam-yadav0206"><i class="fa-brands fa-github"></i></a></li>
                <li><a href="https://www.linkedin.com/in/shivam-yadav-348a65220/"><i class="fab fa-linkedin"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="team-member">
            <div class="main-content">
              <img src="../assests/images/member2.png" alt="member2">
              <span class="category">SDE @ Monotype</span>
              <h4>Satyam Kumar</h4>
              <ul class="social-icons">
                <li><a href="#"><i class="fab fa-facebook"></i></a></li>
                <li><a href="https://github.com/satyamy846"><i class="fa-brands fa-github"></i></a></li>
                <li><a href="https://www.linkedin.com/in/satyam-kumar-883190158/"><i class="fab fa-linkedin"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="team-member">
            <div class="main-content">
              <img src="../assests/images/member3.png" alt="member3">
              <span class="category">Full Stack Developer</span>
              <h4>Amber Sinha</h4>
              <ul class="social-icons">
                <li><a href="#"><i class="fab fa-facebook"></i></a></li>
                <li><a href="https://github.com/amber1405"><i class="fa-brands fa-github"></i></a></li>
                <li><a href="https://www.linkedin.com/in/amber-sinha-749238224/"><i class="fab fa-linkedin"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default{

}
</script>


<style>
/* 
---------------------------------------------
Team Style
--------------------------------------------- 
*/



.team {
  margin-top: 100px;
    padding-top: 140px;
}

.team-member {
  position: relative;
}

.team-member:hover img {
  top: -120px;
}

.team-member img {
  max-width: 220px;
  border-radius: 50%;
  position: absolute;
  top: -110px;
  left: 50%;
  transform: translateX(-110px);
  transition: all .3s;
}

.team-member .main-content {
  border-radius: 25px;
  padding: 140px 30px 40px 30px;
  background-color: #f1f0fe;
  text-align: center;
}

.team-member .main-content span.category {
  color: #7a6ad8;
  font-size: 15px;
}

.team-member .main-content h4 {
  font-size: 22px;
  font-weight: 600;
  margin-top: 8px;
  margin-bottom: 15px;
}

.team-member .main-content ul li {
  display: inline-block;
  margin: 0px 2px;
}

.team-member .main-content ul li a {
  background-color: #fff;
  color: #7a6ad8;
  display: inline-block;
  text-align: center;
  line-height: 40px;
  font-size: 18px;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  transition: all .3s;
}

.team-member .main-content ul li a:hover {
  background-color: #7a6ad8;
  color: #fff;
}
.row{
  display: flex;
  justify-content: space-around;
}
.main-content{
  border: 2px solid rgb(36, 36, 78);

}
.main-content img{
  border: 2px solid rgb(36, 36, 78);
}


</style>