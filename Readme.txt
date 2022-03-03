     <div class="uk-margin">
    <div class="uk-section"><div class="owl-carousel owl-theme">
        <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
         <div class="item">
            <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                <h3 class="uk-card-title">Credit Card Name</h3>
                <p>Current Balance</p>
                <h3>$000,000,000.00</h3>
            </div>
          
      </div>
    </div>
      </div>
    </div>











.uk-section {
  background-color: #666
}
.owl-carousel {
  position: relative;
  margin-top: 30px;
}
.owl-nav {
  position: absolute;
  top: -60px;
  left: 10px;
}
.uk-card-primary {
  border-radius: 8px;
}
h3 {
  margin-top: 10px
}
.uk-card > :last-child {
  margin-top:0;
  margin-bottom: 10px
}
p {
  margin-top: 30px;
  margin-bottom: 0;
}
.owl-next {
  background: #3286f0;
}
.owl-theme .owl-nav [class*='owl-'] {
  background: #383838;
}
.owl-dots {
  margin-top: 30px;
}
.uk-card-title {
  padding-bottom: 20px
}










  $('.owl-carousel').owlCarousel({
    loop:false,
  stagePadding: 15,
    margin:10,
    nav:true,
  navText : ['<span class="uk-margin-small-right uk-icon" uk-icon="icon: chevron-left"></span>','<span class="uk-margin-small-left uk-icon" uk-icon="icon: chevron-right"></span>'],
    responsive:{
        0:{
            items:1
        },
        640:{
            items:2
        },
      960:{
            items:3
        },
        1200:{
            items:4
        }
    }
});






   <div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
                  <div class="modal-dialog" role="document">
                      <div class="modal-content">
                          <div class="modal-header">
                              <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                  <span aria-hidden="true">&times;</span>
                              </button>
                              <h4 class="modal-title" id="myModalLabel">Login form</h4>
                          </div>
                          <div class="modal-body">
                              <form>
                                  <div class="form-group">
                                      <label for="email">Email address</label>
                                      <div class="input-group pb-modalreglog-input-group">
                                          <input type="email" class="form-control" id="email" placeholder="Email">
                                          <span class="input-group-addon"><span class="glyphicon glyphicon-user"></span></span>
                                      </div>
                                  </div>
                                  <div class="form-group">
                                      <label for="password">Password</label>
                                      <div class="input-group pb-modalreglog-input-group">
                                          <input type="password" class="form-control" id="pws" placeholder="Password">
                                          <span class="input-group-addon"><span class="glyphicon glyphicon-lock"></span></span>
                                      </div>
                                  </div>
                              </form>
                          </div>
                          <div class="modal-footer">
                              <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                              <button type="button" class="btn btn-primary">Log in</button>
                          </div>
                      </div>
                  </div>
              </div>


<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModalCenter">
  Launch demo modal
</button>




  <div class="row">
            <!--ADD CLASSES HERE d-flex align-items-stretch-->
            <div class="col-md-4 mb-3 d-flex align-items-stretch">
              <div class="card">
               <div class="row">
                 <div class="col-4">
                  <img src="assets/img aset/Mask Group 98.png" width="40px" alt="">
                 </div>
                 <div class="col-8">
                  <img src="assets/img aset/Group 2913.png" width="110px" alt="">
                 </div>
               </div>
                <div class="card-body d-flex flex-column">
                  <h5 class="card-title">Dōtonbori Canal</h5>
                  <p class="card-text mb-4">Is a manmade  </p>
                  <a href="#" class="btn btn-primary mt-auto align-self-start">Book now</a>
                </div>
              </div>
            </div>
            <!--ADD CLASSES HERE d-flex align-items-stretch-->
            <div class="col-md-4 mb-3 d-flex align-items-stretch">
              <div class="card">
                <img src="https://i.postimg.cc/4xVY64PV/porto-timoni-double-beach-corfu-greece-700.jpg" class="card-img-top" alt="Card Image">
                <div class="card-body d-flex flex-column">
                  <h5 class="card-title">Porto Timoni Double Beach</h5>
                  <p class="card-text mb-4">Near Afionas village, on the west coast of Corfu island. The two beaches form two unique bays. The turquoise color of the sea contrasts to the high green hills surrounding it.</p>
                  <a href="#" class="btn btn-primary mt-auto align-self-start">Book now</a>
                </div>
              </div>
            </div>
            <!--ADD CLASSES HERE d-flex align-items-stretch-->
            <div class="col-md-4 mb-3 d-flex align-items-stretch">
              <div class="card">
                <img src="https://i.postimg.cc/TYyLPJWk/tritons-fountain-valletta-malta-700.jpg" class="card-img-top" alt="Card Image">
                <div class="card-body d-flex flex-column">
                  <h5 class="card-title">Tritons Fountain</h5>
                  <p class="card-text mb-4">Located just outside the City Gate of Valletta, Malta. It consists of three bronze Tritons holding up a large basin, balanced on a concentric base built out of concrete and clad in travertine slabs.</p>
                  <a href="#" class="btn btn-primary mt-auto align-self-start">Book now</a>
                </div>
              </div>
            </div>
          </div>









#sellers  .controls-right a{
 background-color: #94C52E;
  color: #FFFFFF;
  padding: 2px 4px 2px 4px;
  border-radius: 3px;
  
   
}
 
#sellers .card h2{
  font-size: 40px;
  font-weight: 600;
  color: #414A54;
}
#sellers .card p{
  font-weight: 500;
  font-size: 20px;
 }
#sellers .card .btn{
 width: 100%;
 font-size: 20px;
}










  <div class="col-md-4 px-lg-3" style="float:left">
                <div class="card mb-2 text-center">
                  <h2 class="card-title mt-4">8 Yard skip</h2>
                  <img class="card-img-top px-3 p-lg-5" src="assets/img aset/Group 2910.png" alt="Card image cap">
                  <div class="card-body">

                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                      card's content.</p>
                    <a class="btn btn-primary">Book Now</a>
                  </div>
                </div>
              </div>

              <div class="col-md-4 mt-3 mt-md-0 px-lg-3" style="float:left">
                <div class="card mb-2 text-center">
                  <h2 class="card-title mt-4">6 Yard skip</h2>
                  <img class="card-img-top px-3 p-lg-5" src="assets/img aset/Group 2910.png" alt="Card image cap">
                  <div class="card-body">

                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                      card's content.</p>
                    <a class="btn btn-primary">Book Now</a>
                  </div>
                </div>
              </div>

              <div class="col-md-4 mt-3 mt-md-0 px-lg-3" style="float:left">
                <div class="card mb-2 text-center">
                  <h2 class="card-title mt-4">4 Yard skip</h2>
                  <img class="card-img-top px-3 p-lg-5" src="assets/img aset/Group 2910.png" alt="Card image cap">
                  <div class="card-body">

                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                      card's content.</p>
                    <a class="btn btn-primary">Book Now</a>
                  </div>
                </div>
              </div>





<div class="container">
  <div class="row">
    <div class="col-md-3 col-6  text-center">
         <div class="test">
       <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
         <p>bhgffyghg</p>
         <i class="fas fa-check-circle   mx-auto"></i></button>
    
      
    
     </div>
    </div>
    <div class="col-md-3 col-6 text-center ">
        <div class="test">
       <button type="button" class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
         <p>bhgffyghg</p>
         <i class="fas fa-check-circle   mx-auto"></i></button>
    
      
    
     </div>
    </div>
    <div class="col-md-3 col-6 text-center  d-block mx-auto ">
        <div class="test">
       <button type="button" class="btn btn-outline-primary"><h6>affffyghghg</h6>
         <p>bhgffyghg</p>
         <i class="fas fa-check-circle   mx-auto"></i></button>
    
      
    
     </div>
    </div>
    <div class="col-md-3 col-6 text-center ">
        <div class="test">
       <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
         <p>bhgffyghg</p>
         <i class="fas fa-check-circle   mx-auto"></i></button>
    
      
    
     </div>
    </div>
  </div>
</div>





 <section id="booking" class="booking">
    <div class="container ">
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
     

        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row mx-5 my-3">
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center">
                   <div class="test h-100 ">
                 <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
                   <p>bhgffyghg</p>
                   <i class="fas fa-check-circle   mx-auto"></i></button>
              
                
              
               </div>
              </div>
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center ">
                  <div class="test h-100 ">
                 <button type="button"  class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
                   <p>bhgffyghg <br>cddsaa</p>
                   <i class="fas fa-check-circle   mx-auto"></i></button>
              
                
              
               </div>
              </div>
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center">
                <div class="test h-100 ">
              <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
                <p>bhgffyghg</p>
                <i class="fas fa-check-circle   mx-auto"></i></button>
           
             
           
            </div>
           </div>
           <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center ">
               <div class="test h-100 ">
              <button type="button"  class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
                <p>bhgffyghg <br>cddsaa</p>
                <i class="fas fa-check-circle   mx-auto"></i></button>
           
             
           
            </div>
           </div>
              <div class="col-md-3 col-lg-2 col-12 text-center  my-2 my-lg-0 ">
                <div class="test h-100 ">
                  <button type="button"  class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
                    <p>bhgffyghg <br>cddsaa</p>
                    <i class="fas fa-check-circle   mx-auto"></i></button>
               
                 
               
                </div>
              </div>
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center ">
                  <div class="test h-100">
                 <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
                   <p>bhgffyghg</p>
                   <i class="fas fa-check-circle   mx-auto"></i></button>
              
                
              
               </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row mx-5 my-3">
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center">
                   <div class="test h-100 ">
                 <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
                   <p>bhgffyghg</p>
                   <i class="fas fa-check-circle   mx-auto"></i></button>
              
                
              
               </div>
              </div>
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center ">
                  <div class="test h-100 ">
                 <button type="button"  class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
                   <p>bhgffyghg <br>cddsaa</p>
                   <i class="fas fa-check-circle   mx-auto"></i></button>
              
                
              
               </div>
              </div>
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center">
                <div class="test h-100 ">
              <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
                <p>bhgffyghg</p>
                <i class="fas fa-check-circle   mx-auto"></i></button>
           
             
           
            </div>
           </div>
           <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center ">
               <div class="test h-100 ">
              <button type="button"  class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
                <p>bhgffyghg <br>cddsaa</p>
                <i class="fas fa-check-circle   mx-auto"></i></button>
           
             
           
            </div>
           </div>
              <div class="col-md-3 col-lg-2 col-12 text-center  my-2 my-lg-0 ">
                <div class="test h-100 ">
                  <button type="button"  class="btn btn-outline-primary disabled"><h6>ffffyghghg</h6>
                    <p>bhgffyghg <br>cddsaa</p>
                    <i class="fas fa-check-circle   mx-auto"></i></button>
               
                 
               
                </div>
              </div>
              <div class="col-md-3 col-lg-2 col-12 my-2 my-lg-0 text-center ">
                  <div class="test h-100">
                 <button type="button" class="btn btn-outline-primary"><h6>ffffyghghg</h6>
                   <p>bhgffyghg</p>
                   <i class="fas fa-check-circle   mx-auto"></i></button>
              
                
              
               </div>
              </div>
            </div>
          </div>
          
        </div>

        <a class="carousel-control-prev" style="background-color: #252A3E; " href="#carouselExampleControls" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" style="background-color: #252A3E;"  href="#carouselExampleControls" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
        
         
         
         
        </div>
    </div>
   </section>



<!-- Modal Login form Section -->
<div class="modal fade" id="login-model"  tabindex="-1" role="dialog" aria-labelledby="login-modelTitle" aria-hidden="true">
  <div class="modal-dialog modal modal-dialog-centered"role="document">
    <div class="modal-content">
      
      <div class="login-block">
        <div class="row">
          <div class="col-md-6 col-12 order-2 order-md-1 d-flex align-items-center" style=" background-image: linear-gradient(#95C530, #3A8D36);">
          
           <div class="container my-md-0 my-5 sign-in-sec text-center">
            <h5>Welcome!</h5>
            <p>To keep connected with us please login with your personal</p>
           
            <!-- Button trigger modal -->
<button type="button" class="btn btn-outline-light" data-toggle="modal" data-target="#exampleModalCenter">
  Sign up
</button>
           </div>  
          </div>
          <div class="col-md-6 order-1 order-md-2 col-12">
            <button type="button" class="close " data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
            <div class="row mt-4">
              <div class="col-md-12">
                <h3 class="text-center heading">Create an Account</h3>
            </div>
                <div class="col-sm-12">
                    <form class="md-float-material form-material" action="#" method="POST">
                        <div class="auth-box card">
                            <div class="card-block">
                              
                               <div class="form-group form-primary"> <input type="text" class="form-control" name="email" value="" placeholder="Email Address" id="email"> </div>
                               
                               
                                <div class="form-group form-primary"> <input type="password" class="form-control" name="password" placeholder="Password" value="" id="password"> </div>
                                
                                <div class="terms-condtions">
                                  <div class="my-2 form-check d-flex flex-row"> <input class="form-check-input" type="checkbox" value="" id="services"> <label class="form-check-label ms-2" for="services"> I have agree to the <a href="">terms</a> & <a href="">privacy policy</a> </label> </div>
                              </div>
                                <div class="row">
                                    <div class="col-md-12"> <input type="submit" class="btn btn-primary btn-md btn-block waves-effect text-center m-b-20" name="submit" value="Sign in"> <!-- <button type="button" class="btn btn-primary btn-md btn-block waves-effect text-center m-b-20"><i class="fa fa-lock"></i> Signup Now </button> -->
                                    </div>
                                </div>
                                 
                               
                            </div>
                        </div>
                    </form>
                </div>
            </div>
          </div>
        </div>
           
        
    </div>
    </div>
  </div>
</div>
<!-- End Login form Section -->










 <h5>Can I skip it?</h5>
         <div class="ml-md-2">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
          <div class="row">
            <div class="col-md-4">
              <ul class="fa-ul">
                <li><span class="fa-li"><i class="fas fa-check-square"></i></span>List icons can</li>
                <li><span class="fa-li"><i class="fas fa-check-square"></i></span>be used to</li>
                
              </ul>
            </div>
            <div class="col-md-4">
              <ul class="fa-ul">
                <li><span class="fa-li"><i class="fas fa-check-square"></i></span>List icons can</li>
                <li><span class="fa-li"><i class="fas fa-check-square"></i></span>be used to</li>
                
              </ul>
            </div>
            <div class="col-md-4">
              <ul class="fa-ul">
                <li><span class="fa-li"><i class="fas fa-check-square"></i></span>List icons can</li>
              
              </ul>
            </div>
          </div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo ad soluta pariatur veritatis dolore nulla similique expedita voluptatum, exercitationem magni quibusdam quos nobis consequatur officia distinctio ea officiis quidem ipsa optio fugit. Quam, minima vero quidem delectus laboriosam facilis atque iste sunt voluptates omnis sed.</p>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla, quia. Iure, sequi ipsam est qui nihil fuga voluptates harum nisi asperiores veritatis dolorem! Quidem, excepturi?</p>
         </div>