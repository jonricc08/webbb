

<template>

 <link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
  

   <header>
            <div class = "wrapper">
                <div class = "icon">
                    <i class='fas fa-user-secret' style='font-size:55px;color:rgb(255, 255, 255)'></i>
                </div>
                <div class = "vert-line"></div>
                <div class = "text">
                    <h2>JONRIC MANISAN</h2>
                    <p>Bachelor of Science in Information Technology</p>
                </div>
                <div class = "vert-line"></div>
                <nav>
                    <ul>
                        <li><a href = "#">AboutMe</a></li>
                        <li><a href = "#">Goal</a></li>
                        <li><a href = "#">Crush</a></li>
                        <li><a href = "#">contact</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <section id = "intro" class = "page">
            <span class = "close-btn">
                <i class = "fas fa-times"></i>
            </span>
            <h2 class = "title">AboutMe</h2>
            <img src = "images/4.jpg" alt = "">
            <p>I am Jonric Manisan</p>
            <p>Programmer</p>
            <p>Gamer</p>
            <p>Music Lover</p>
            <p>Pet Lover</p>
            <img src = "images/5.jpg" alt = "">
            <p></p>
            <p></p>
        </section>

        <section id = "work" class = "page">
            <span class = "close-btn">
                <i class = "fas fa-times"></i>
            </span>
            <h2 class = "title">My Goal</h2>
           <p>Graduate in Lasalle University</p>
           
            <article>
                <img src = "images/1.jpg">
            
            </article>
            <p>Find a Job!</p>
            <article>
                <img src = "images/work-2.jpg">
                <p></p>
                
            </article>
            <p>Travel</p>
            <article>
                <img src = "images/3.jpg">
                <p></p>
                
            </article>
        </section>

        <section id = "about" class = "page">
            <span class = "close-btn">
                <i class = "fas fa-times"></i>
            </span>
            <h2 class = "title">Crush!</h2>
            <img src = "images/2.jpg">
            <h3>Liza Soberano</h3>
            <h3>Sheeesshh!</h3>
            
        </section>

        <section id = "contact" class = "page">
            <span class = "close-btn">
                <i class = "fas fa-times"></i>
            </span>
            <h2 class = "title">contact</h2>
            <p>Call Me 50 load lang 09052164858</p>

            <form>
                <label for = "name">Name</label>
                <input type = "text" id = "name">
                <label for = "email">Email</label>
                <input type = "email" id = "email">
                <label for = "dob">Date Of Birth</label>
                <input type = "date" id = "dob">
                <label for = "message">Message</label>
                <textarea id = "message" name = "message" rows = "4"></textarea>

                <input type = "submit" value = "Send">
            </form>
        
        </section>
        

       
</template>

<script>
 

export default {
  name: 'App',
  components: {
 
  }
}
</script>


