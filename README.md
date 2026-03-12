This project is a simple Laundry Service landing page created using HTML and CSS. The page contains a fixed navigation bar at the top with a logo, menu links, and a username button. Below the navigation bar there is a hero section divided into two parts. The left side shows the main heading, a short description about the laundry service, and a button to book a service. The right side displays an illustration image related to laundry services. The main goal of this project is to practice webpage layout, element positioning, and basic styling using CSS.
In the website use @media to make this responsive for all screen type.


This is live project link:
https://task5-three-beta.vercel.app/











/* media quary for width <= 1024px or max-width: 1024px */
/* @media (width <= 1024px) {
  
} */
@media (max-width: 1024px) {
  .nav {
    display: flex;
  }
  .menu {
    font-size: 12px;
  }
  .right-view {
    position: relative;
    width: 50vw;
    height: 100%;
    text-align: center;
  }

  .right-view img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scaleX(-1);
    width: 55vw;
    height: auto;
  }
}

/* for tablet */
/* media quary for width <= 768px or max-width: 768px */
/* @media (width <= 768px) {
  
} */
@media (max-width: 768px) {
  .nav {
    display: flex;
  }
  .user-wrapper {
    font-size: 12px;
  }
  .menu {
    font-size: 12px;
  }
  .left-view > .left-view-content > h1 {
    font-size: 38px;
    line-height: 45px;
  }

  .left-view > .left-view-content > h2 {
    font-size: 30px;
  }

  .left-view > .left-view-content > p {
    line-height: 1.5;
  }

  .left-view > .left-view-content > button {
    padding: 20px 60px;
    font-size: 14px;
  }
  .right-view {
    position: relative;
    width: 50vw;
    height: 100%;
    text-align: center;
  }

  .right-view img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scaleX(-1);
    width: 45vw;
    height: auto;
  }
}

/* for Mobile */
/* media quary for width <= 480px or max-width: 480px */
/* @media (width <= 480px) {
  
} */
@media (max-width: 480px) {
  nav {
    /* display: flex;
    justify-content: space-between; 
    align-items: center; 
    padding: 0 10px;  */
    padding: 0 20px;
  }
  .menu {
    display: none;
  }
  .user-section {
    position: absolute;
    top: 30%;
    right: 0;
    width: auto;
    padding-right: 20px;
  }
  .user-wrapper {
    font-size: 14px; 
    padding: 8px 15px; 
    border-radius: 10px;
  }
  .menu {
    display: none;
  }
  .hero-section {
    display: flex;
    flex-direction: column;
  }
  .left-view {
    padding: 0;
    margin-top: 50px;
  }
  .left-view > .left-view-content{
    /* width: 100%; */text-align: le;
  }
  .left-view, .right-view  {
    width: 100%;
  }
  .left-view > .left-view-content > h1 {
    font-size: 38px;
    line-height: 45px;
  }

  .left-view > .left-view-content > h2 {
    font-size: 30px;
  }

  .left-view > .left-view-content > p {
    line-height: 1.5;
  }

  .left-view > .left-view-content > button {
    padding: 20px 60px;
    font-size: 14px;
  }

  .right-view img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scaleX(-1);
    width: 85vw;
    height: auto;
  }
}
