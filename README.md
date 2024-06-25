@charset "UTF-8";

.yellow{

	background-color:#FFF3C7;

}
/* /////////////////////////////////////////////////////// */

.logo >a {
	
	display:block;
	text-decoration: none;
	font-size: 35px;
	margin-bottom: 15px;
	
}

.nav-menu {
    display: grid;
    grid-template-columns: repeat(2, 1fr); 
    grid-template-rows: repeat(3, 1fr); 
    gap: 10px; 
    list-style: none; 
    padding: 0;
}

.nav-menu > li {
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.nav-menu > li > a {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%; 
    height: 100%; 
}

.nav-menu > li > a > img {
    max-width: 100%; 
    max-height: 100%; 
}

.nav-menu > li:hover {
    background-color: #e0e0e0; 
}





/* /////////////////////////////////////////////////////// */






body {

    margin: 0;

    font-family: 'Arial', sans-serif;

    background-color: #f0f2f5;

}



.wrap {

    display: grid;

    grid-gap: 20px;

    min-height: 100vh;

    grid-template-columns: 250px 1fr 250px;

    grid-template-rows: 70px auto 1000px 1fr 1fr 50px;

    grid-template-areas: 

        "header header header"

        "menu main top"

        "menu main aside"

        "menu main bottom"

        "footer footer footer";

    padding: 20px;

    box-sizing: border-box;

}



.wrap > div, .wrap > header, .wrap > footer {

    padding: 20px;

    border-radius: 10px;

     background-color: #FFF3C7; 

    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);

}



.header {

    grid-area: header;

    color: white;

    text-align: center;

    display: flex;

    justify-content: center;

    align-items: center;

    font-size: 1.5em;

    font-weight: bold;

    border-radius: 10px;

}

.header .logo {

	display:flex;

    position: absolute;

    left: 40px;

    top: 65px;

    transform: translateY(-50%);

}



.header .logo img {

    height: 50px; 

}



.menu {

    grid-area: menu;

}



.navs {

    display: flex;

    flex-direction: column;

    align-items: center;

    height:50%;
    
    border-bottom: white solid 1px; /* //////////////////////// */

	

}





.profile {

    display: flex;

    flex-direction: column;

    align-items: center;

    margin-bottom: 20px;
    
    border-bottom: white  solid 1px; /* //////////////////////// */

}



.profile-photo {

    width: 100px;

    height: 100px;

    border-radius: 50%;

    margin-bottom: 10px;

}



.profile-info {

    text-align: center;
   

}



.profile-info .name {

    font-size: 1.2em;

    font-weight: bold;

}



.profile-info .title {

    font-size: 0.9em;

    color: #666;

}



.last-login {

    font-size: 0.8em;

    color: #666;

    margin: 10px 0;

}



.profile-links {

    display: flex;

    align-items: center;

}



.profile-links a {

    color: #007bff;

    text-decoration: none;

    margin: 5px 10px; 

    transition: color 0.3s;

    position: relative; 

}





.profile-links a:hover {

    color: #0056b3;

}



.attend{

	display:grid;

	padding: 50px 50px;

	border: 1px solid black;

	background-color: #007bff;

    color: white;

    margin: 10px 0;

    text-align: center;

    border-radius: 5px;

    cursor: pointer;

    transition: background-color 0.3s ease;

}


/* 
.nav-menu {

    display: flex;

    flex-direction: column;

    align-items: stretch;

    padding: 0;

    margin: 0;

    list-style: none;

} */


/* 
////////////////////////
.nav-menu > a> li {

   

    padding: 10px 20px;

    margin: 10px 0;


    border-radius: 5px;

    cursor: pointer;

    transition: background-color 0.3s ease;

}



.nav-menu > a>li:hover {

    background-color: #0056b3;

} */



.main {

    grid-area: main;

}



.top {

    grid-area: top;

    margin-bottom: 20px;

}



.aside {

    grid-area: aside;

    margin-bottom: 20px;

}



.bottom {

    grid-area: bottom;

}



.footer {

    grid-area: footer;

    background-color: #007bff;

    color: white;

    text-align: center;

    display: flex;

    justify-content: center;

    align-items: center;

    font-size: 1em;

    font-weight: bold;

    border-radius: 10px;

}
