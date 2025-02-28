# collage
this is my first repository
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sidebar </title>
    <link rel="stylesheet" href="first.css">
     

    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
</head>
<body>
    <aside class="sidebar">
            <div class="side_header">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQCv9wzYolrynmOS6nHXVkI6L9P7G3zBT2Wsw&s" alt="logo">
                <h2>Coding lab</h2>            
            </div>

        <ul class="sidebar_link">
        <h4><span>Maine Menu</span>
        <div class="menu_seperator"></div>
    </h4>

                <li><a href="#"><span class="material-symbols-outlined">
                    dashboard
                    </span>Dashboard</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    Overview
                    </span>Overview</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    folder
                    </span>Project</a>
                </li>

     <h4><span>General</span>
        <div class="menu_seperator"></div>
    </h4>

                <li><a href="#"><span class="material-symbols-outlined">
                    Groups
                    </span>groups</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                monitoring
                    </span>Analytics</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    move_up
                    </span>Transfer</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    flag
                    </span>All Reports</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    Notifications_active
                    </span>Notifications </a>
                </li>
    <h4><span>Accounts</span>
        <div class="menu_seperator"></div>
    </h4>
                <li><a href="#"><span class="material-symbols-outlined">
                    account_circle
                    </span>Profile</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    settings
                    </span>Settings</a>
                </li>
                <li><a href="#"><span class="material-symbols-outlined">
                    logout
                    </span>Logout</a>
                </li>
        </ul>

                <div class="user_account">
                    <div class="user_profile">
                        <img src="https://t4.ftcdn.net/jpg/00/50/92/03/360_F_50920378_hep474tI6wHWufJNmRWycIEDLBdHFEcn.jpg" alt="photo">
                        <div class="user_detail">
                            <h3>Nazneen Khan</h3>
                            <span>Web Developer</span>
                        </div>
                    </div>
                </div>
    </aside>


    
</body>
</html>       //css 
@import url('https://fonts.googleapis.com/css2?family=Playwrite+VN:wght@100..400&family=Poppins&display=swap');

* {
    font-family: "Poppins", serif;
    /* box-sizing: border-box; */
    padding: 0;
    margin: 0;
  }

  .side_header img{
    height: 30px;
    border-radius: 50%;
    box-shadow: 1px 1px 2px hwb(178 7% 2%);
    margin: 5px 5px 5px 20px;

  }
  body{
    background:#d2d2d2 ;
    min-height: 100vh;
  }
  .sidebar{
    height: 100%;
    width: 60px;
    position: fixed;
    background: #161a2d;
    top: 0;
    left: 0;
    /* padding: 25px 25px; */
    display: flex;
    flex-direction: column;
    overflow-x: hidden;
  }
  .sidebar:hover{
    width: 200px;
    transition:  all 0.4s ease;

  }
  .sidebar_link h4 span{
opacity: 0;
  }

.sidebar:hover .sidebar_link h4 span{
    opacity: 1;
      }
    

  .side_header h2{
    font-size: 1.25rem;
    font-weight: 600;
    color: #fff;
    margin-left: 23px;
  }
  

  .side_header{
    display: flex;
    align-items: center;
  }

.sidebar_link h4{
    color: #fff;
    font-weight:600;
    margin-left: 10px;
    white-space: nowrap;
     position: relative; 
  }


  .sidebar:hover .sidebar_link .menu_seperator{
    transform: scalex(0);
    transition-delay: 0s;

  }

  .sidebar_link .menu_seperator{
    position: absolute;
    left: 0;
    top: 50%;
    width: 100%;
    height: 1px;
    transform: scaleX(1);
    transform: translatey(-50%);
    background: #333578;
      transform-origin: right;
      transition-duration: 0.2s;

  }
  h4{
    font-size: 13px;
  
  }
  .sidebar_link{
    list-style: none;
    margin-top: 20px;
    height: 60%;
    overflow-y: auto;
    scrollbar-width: none;
  }

  .sidebar_link li a{
    display: flex;
    align-items: center;
    gap: 0 20px;
    color: #dbd4d4e3;
    font-weight: 100;
    font-size: 15px;
    padding: 10px 5px;
    white-space: nowrap;
    text-decoration: none;
    margin-left: 20px;
    
  }
  .sidebar_link li a:hover{
    background: #ffffff2d;
    color: #fff;
    border-radius: 4px;
  }

  .user_account{
    margin-top: 20px;
    padding: 12px 10px;
    margin-left: 5px;

  }
  
.user_account .user_profile{
  color: #e5dede;
  display: flex;
  align-items: center;
}

.user_profile img{
  width: 42px;
  border-radius: 50%;

}

.user_profile h3{
  font-size: 1rem;
  font-weight: 600;
}
.user_profile  span{
  font-size: 0.775rem;
  font-weight: 600;
  display: block;
  margin-top: 0;

}
.user_detail{
  margin-left: 10px;
  white-space: nowrap;

}

.sidebar:hover .user_account{
  background: #ffffff2d;
  border-radius: 5px;
}



its a sidebar
