<template>
    <header class="header">
        <div class="header__nav">  
        <img src="../assets/swiggy-1.svg" alt="" class="logo"> 
        <span class="nav__txt">Swiggy</span>
        <span class="divider"></span>
        <img src="../assets/location.svg" alt="" class="location">
        <span class="nav__location">Setup your precise location</span>
        <img src="../assets/down.svg" alt="" class="down"> 
         <form action="#" class="search">
            <input type="text" class="search__input" placeholder="Search for resturant and food">
            <button class="search__button">
               <img src="../assets/search.svg" alt="" class="search__icon">
            </button>
         </form>
         <img src="../assets/user.svg" alt="" class="user__icon">
        </div>
    
        <div class="header-banner">
            <div class="header-banner__txt">
                <span>Order Food</span><br>
                <span>Online in </span><br>
                <span>Mumbai</span><br>
                <span> <img src="../assets/curve.svg" alt="" class="curve"></span>
               
        
               
               </div>
            <div class="header-banner__img">
              <img src="https://res.cloudinary.com/swiggy/image/upload/fl_lossy,f_auto,q_auto,w_1002,h_600/v1678428358/portal/m/seo_web/dweb_header" alt="" class="img">
            </div>
        </div>
     
    </header>
  </template>
  

  
  <style lang="scss">
  .header-banner{
    width: 100%;
    &__img{
     flex: 1;
     align-items: flex-start;
      img{
        max-height: 100%;
        margin-left: -12rem;

      }
    }
    font-family: "Basis Grotesque Pro", Arial, sans-serif;;
    display: flex;
        height: 30rem;
        background: linear-gradient(to bottom , white , rgb(195, 166, 244));
        border-bottom-left-radius: 25px;
        border-bottom-right-radius: 25px;
            &__txt{
                 flex: 1;
                 text-align:start;
                  // border : 1px solid orangered;
                 font-size: 48px;
                  line-height: 48px;
                  color: rgba(2, 6, 12, 0.75);
                  font-weight: 600;
                  letter-spacing: -0.43px;
                  padding: 6rem 4rem 0 0 ;
                  padding-left: 20rem;
                  -webkit-font-smoothing: antialiased;
        &>span .curve{
          display:inline-block;
          height: 1rem; 
        }
    }
    
  }
    .header__nav{
    height: 8rem;
    display: flex;
   
    
    align-items: center;
    justify-content: center;
    border-bottom: 1px solid #ccc;
  }
  .logo{
    height:3.56rem;
    width: 2.35rem ;
    margin-left: -10rem;
  }
  .location{
    height:2rem;
    width: 2.35rem ;
    margin-left: 2rem;
    margin-right: 2rem;
  }
  .down{
    height:1rem;
    width: 1.5rem ;
    margin-left: 1rem;
   
  }
  .user__icon{
    margin-left: 3rem;
    height:5rem;
    width: 5rem ;
  }
  
  .search{
    display: flex;
    
    margin-left: 2rem;
   
    &__input{
      
        width: 49.5rem;
        background-color: #eae8e8;
        height: 4.8rem;
        border-radius: 1.2rem;
        border: none;
        border-color: transparent;
        margin-left: 15rem;
        &:focus{
          outline: none;
        }
    }
    &__button{
        border: none;
    }
    &__icon{
        height:3.56rem;
        width: 2.35rem ;
        margin-left: -4rem;
    }

  }
  
  .nav{
    &__txt{
        margin-left: 1rem;
        font-family: "Basis Grotesque Pro", Arial, sans-serif;
        font-weight: 700;
        font-size: 2.5rem;
       // border-right: 1px solid rgb(155, 154, 154);
        padding: 1rem;
    }
    &__location{
        font-size: 1.8rem;
        font-weight: 500;
        margin-left: -1rem;
        font-family: "Basis Grotesque Pro", Arial, sans-serif;
        
        
    }
   
  }
  .divider {
 width: 0;
 height: 2em;
 border-left: 1px solid #ccc;
 
}
::placeholder {
    font-family: "Basis Grotesque Pro";
    font-size: 14px;
    font-weight: 400;
    line-height: 18px;
    padding: 1.5rem;
    letter-spacing: -0.3px;
    color:  #02060C99
}
  </style>