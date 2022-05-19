<template>

    <div class="border">
    
        <div class="utility hov-e">
            <ul class="icons">
                <li><i class="fa-solid fa-ruler"></i></li>
                <li><i class="fa-solid fa-life-ring"></i></li>
                <li><i class="fa-solid fa-book"></i></li>
                <li><i class="fa-solid fa-cart-shopping"></i></li>
            </ul>
        </div>

        <nav id="start" class="navbar navbar-expand-lg bg-light d-flex justify-content-center ">
            <div class="d-flex justify-content-between">
                <a class="navbar-brand" href="#">
                    <img src="../assets/images/dark-logo.png" class="w-50" alt="">
                </a>
                <div class="collapse navbar-collapse " id="navbarScroll">
                
                    <li class="nav-item dropdown">
                        <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            {{myArray[0].name}}
                        </a>
                        <ul class="dropdown-menu thiss animate slideIn" aria-labelledby="navbarScrollingDropdown">
                            <div class="row">
                            <div class="col-4">
                                <ul>
                                    <li class="lineHeight">MaxCoach Education <span class="hot">HOT</span></li>
                                    <li class="lineHeight">Course Portal</li>
                                    <li class="lineHeight">Distant Leaning <span class="hot">HOT</span></li>
                                    <li class="lineHeight">Multimedia Pedagogy</li>
                                    <li class="lineHeight">Modern Schooling</li>
                                    <li class="lineHeight">Remote Training</li>
                                    <li class="lineHeight">Health Coaching</li>
                                    <li class="lineHeight">Gym Coaching</li>
                                    <li class="lineHeight">Business</li>
                                </ul>
                            </div>


                            <div class="col-4">
                                <ul>
                                    <li class="lineHeight">Artist</li>
                                    <li class="lineHeight">Kitchen Coach</li>
                                    <li class="lineHeight">Motivation</li>
                                    <li class="lineHeight">Dancing <span class="new">NEW</span></li>
                                    <li class="lineHeight">Guitar <span class="new">NEW</span></li>
                                    <li class="lineHeight">Yoga <span class="new">NEW</span></li>
                                    <li class="lineHeight">Photography <span class="new">NEW</span></li>
                                    <li class="lineHeight">Personal Finance <span class="new">NEW</span></li>
                                </ul>
                            </div>

                            <div class="col-4 ">
                                <img src="../assets/images/homepages-mega-menu-image-alt.jpg" class="img" alt="">
                            </div>
                        </div>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            {{myArray[1].name}}
                        </a>
                    <ul class="dropdown-menu animate slideIn" aria-labelledby="navbarScrollingDropdown">
                        <ul>
                        <li class="lineHeight">Start Here</li>
                        <li class="lineHeight">Success Story</li>
                        <li class="lineHeight">About me</li>
                        <li class="lineHeight">About us 01</li>
                        <li class="lineHeight">About us 02</li>
                        <li class="lineHeight">About us 03</li>
                        <li class="lineHeight">Contact me</li>
                        <li class="lineHeight">Contact us</li>
                        <li class="lineHeight">Purchase Guide</li>
                        <li class="lineHeight">Privacy Policy</li>
                        <li class="lineHeight">Terms of Service</li>
                        </ul>
                    </ul>
                    </li>

                    <li class="nav-item dropdown">
                        <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            {{myArray[2].name}}    
                        </a>
                    <ul class="dropdown-menu animate slideIn" aria-labelledby="navbarScrollingDropdown">
                        <ul>
                        <li class="lineHeight">Courses Grid 01</li>
                        <li class="lineHeight">Courses Grid 02</li>
                        <li class="lineHeight">Courses Grid 03</li>
                        <li class="lineHeight">Memmbership Levels</li>
                        <li class="lineHeight">Become a Teacher</li>
                        <li class="lineHeight">Profile</li>
                        <li class="lineHeight">Checkout</li>
                        <li class="lineHeight">Single Layout</li>
                        </ul>
                    </ul>
                    </li>

                    <li class="nav-item dropdown">
                        <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            {{myArray[3].name}}
                        </a>
                    <ul class="dropdown-menu animate slideIn" aria-labelledby="navbarScrollingDropdown">
                        <ul>
                            <li class="lineHeight">Events</li>
                            <li class="lineHeight">Zoom Meetings</li>
                        </ul>
                    </ul>
                    </li>

                    <li class="nav-item dropdown">
                        <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            {{myArray[4].name}}  
                        </a>
                    <ul class="dropdown-menu animate slideIn" aria-labelledby="navbarScrollingDropdown">
                        <ul>
                            <li class="lineHeight">Blog Grid</li>
                            <li class="lineHeight">Blog Masonry</li>
                            <li class="lineHeight">Blog Classic</li>
                            <li class="lineHeight">Blog List</li>
                        </ul>
                    </ul>
                    </li>

                    <li class="nav-item dropdown ">
                        <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            {{myArray[5].name}}    
                        </a>
                    <ul class="dropdown-menu animate slideIn" aria-labelledby="navbarScrollingDropdown">
                        <ul>
                            <li class="lineHeight">Shop Left Sidebar</li>
                            <li class="lineHeight">Shop Right Sidebar</li>
                            <li class="lineHeight">Cart</li>
                            <li class="lineHeight">Whishlist</li>
                            <li class="lineHeight">Single Product</li>
                        </ul>
                    </ul>
                    </li>

                    <li class="nav-item px-3">
                        <i class="fa-solid fa-circle-user hov" ></i>
                    </li>

                    <form class="d-flex" role="search">
                        <input class="form-control me-2" type="search" placeholder="Search..." aria-label="Search">
                        <i class="fa-solid fa-magnifying-glass glass"></i>
                    </form>
                </div>
            </div>
        </nav>

    </div>
</template>

<script>
import  dati from '../dati.json'

export default {
  
    name:'AppHeader',
    data(){
        return{
          myArray:dati,
          loading:false
          
        }
    }
    
}
</script>

<style lang="scss" scoped>
@import "../styles/vars.scss";
.hot{
  
  font-weight: 700;
  background-color: #f5df2e;
  background-image: linear-gradient(315deg, #f5df2e 0%, #f07654 74%);
  width: 100px;
  height: 50px;
}
.new{
  width: 100px;
  height: 50px;
  background-color: $green;
}
.dropdown-menu.thiss {
  padding: 30px !important;
  width: 1000px !important;
  height: 400px !important;
  transition: 1s;
  
}
.dropdown-menu{
  border-bottom:8px solid $green;
}
 
  li a::after {
    content: "";
    position: absolute;
    display: block;
    height: 0.2em;
    width: 0%;
    bottom: -0.2em;
    transition: all ease-in-out 250ms;
    opacity: 0;
  }
  li a:hover::after {
    opacity: 1;
    width: 60%;
  }
 
.img{
  width: 100%;
  margin-top: 70px;
  
}
.lineHeight{
  line-height: 40px;
}
.hov-e{
  opacity: 0;
}
.hov-e:hover{
  opacity: 1;
}
.hov:hover{
  color: $green;
}
.utility{
  position:fixed;
  right: 0;
  box-shadow: -11px 5px 20px 4px rgba(0,0,0,0.47);
  z-index: 1000;
  
 
  
}
.icons{
  line-height: 40px;
  padding: 10px;
}
.border{
    box-shadow: -11px 5px 20px 4px rgba(0,0,0,0.47);
}
.glass{
    position: relative;
    top:10px;
    right:40px;
    color: $green;
}
.color-nav{
  color: $gray;
}