<template>
  <div>
    <div id="hero"> 
      <img id="logo" src="../assets/img/logo.png" alt="">
      <div id="login-header">
          <a href="">login / sign up</a>
      </div>
      <h1 id="name">Pet-erinar</h1>
    </div>

      <nav id="nav">
        <ul>
          <li><a href="">Home</a></li>
          <li><a href="">About</a></li>
          <li><a href="">Book</a></li>  
        </ul>
      </nav>

  </div>
</template>

<style lang="scss">
body {
  margin: 0;

  div#hero {
    h1#name {
      margin: 0;
      font-size: 20px;
      color: #639198;

    }
    img#logo {
      height: 60px;
    }
  }

    nav#nav {
        border-bottom: 3px solid #639198;
        border-top: 3px solid #639198;
        background-color: #e5f6f8;



      ul {
         padding: 0;
         list-style-type: none;
         li {
            padding: 0 20px;
            display: inline-block;
         }
         a {
            font-weight: 700;
            text-decoration: none;
            color: #639198;

            }
        }
    }
    div#login-header  {
            position: absolute;
            top: 30px;
            right: 35px;
            background-color: #E5F6F8;
            padding: 10px;
            border: 2px solid #639198;
        a {
            text-decoration: none;
            color: #639198;
            font-weight: 600;
        }
    }
}
</style>