<template>
    <footer>
        <div class="back-footer">
            <div class="contatti container">
               <div class="mini-container lista-footer">
                    <h2>Dc Comics

                        <ul>
                            <li>
                                <a href="#">Characters</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movies</a>
                            </li>
                            <li>
                                <a href="#">Tv</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>
                        </ul>
                        
                    </h2>  
                        

                        <div class="lista-footer">
                            <h2>Dc
                                <ul>
                                    <li>
                                        <a href="#">Terms Of use</a>
                                    </li>
                                    <li>
                                        <a href="#">Privacy policy (New)</a>
                                    </li>
                                    <li>
                                        <a href="#">Ad Choices</a>
                                    </li>
                                    <li>
                                        <a href="#">Advertising</a>
                                    </li>
                                    <li>
                                        <a href="#">Jobs</a>
                                    </li>
                                    <li>
                                        <a href="#">subscriptions</a>
                                    </li>
                                    <li>
                                        <a href="#">Talent Workshops</a>
                                    </li>
                                    <li>
                                        <a href="#">CPSC Certificates</a>
                                    </li>
                                    <li>
                                        <a href="#">Ratings</a>
                                    </li>
                                    <li>
                                        <a href="#">Shop Help</a>
                                    </li>
                                    <li>
                                        <a href="#">Contact Us</a>
                                    </li>
                                </ul>
                            </h2>
                        </div>

                        <div class="lista-footer">
                            <h2>Sites
                                <ul>
                                    <li>
                                        <a href="#">DC</a>
                                    </li>
                                    <li>
                                        <a href="#">MAD Magazine</a>
                                    </li>
                                    <li>
                                        <a href="#">DC Kids</a>
                                    </li>
                                    <li>
                                        <a href="#">DC Universe</a>
                                    </li>
                                    <li>
                                        <a href="#">Dc Power Visa</a>
                                    </li>
                                </ul>
                            </h2>
                        </div>
                        <div class="lista-footer">
                            <h2>Shop
                                <ul>
                                    <li>
                                        <a href="#">Shop DC</a>
                                    </li>
                                    <li>
                                        <a href="#">Shop DC Collectibles</a>
                                    </li>
                                </ul>
                            </h2>
                        </div>
               </div>
            </div>

            <!-- BTN FOOTER/SOCIAL LINKS -->
            <div class="linea-footer">
                <div class="container links"> 
                    <div class="btn">
                        <button>Sign-Up Now!</button>
                    </div>

                    <div class="social-list">
                        <div class="follow">
                            <h2>Follow Us</h2>
                        </div>
                        
                        <div class="socials">
                            <ul>
                                <li>
                                    <a href="#">
                                        <img src="@/assets/img/footer-facebook.png" alt="facebook">
                                    </a>
                                </li>
                            </ul>
                        </div>

                    </div>

                </div>
            </div>
        </div>
    </footer>
</template>

<script>


export default {
  name: 'Footer',
};
</script>

<style>
.back-footer{
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    font-family: sans-serif;
}

.container{
    max-width: 1170px;
}

.mini-container{
    width: 50%;

}

.contatti{
padding-top: 1rem;
}

.lista-footer{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    flex-basis: calc(100% / 3 - 5px);
    display: inline-block;
}

.lista-footer h2{
    text-transform: uppercase;
    color: #fff;
    font-size: 17px;
    padding-bottom: 1rem;
}

.contatti ul {
    list-style: none;
}

.contatti ul li{
    margin-bottom: 6px;
}

.contatti ul li a{
    text-decoration: none;
    color: grey;
    font-size: 15px;
    text-transform: none;
}

/* BTN/SOCIAL LINKS */
.linea-footer{
    height: 100px;
    width: 100%;
    background: #303030;
}

.links{
    display: flex;
    align-items: center;
    padding: 1.5rem;
    flex-basis: 100%;

}

.social-list{
    display: flex;
    align-items: center;
    justify-content: end;
}

.btn button{
    padding: 1rem;
    background: #303030;
    outline: none;
    border: 2px solid #0c7cec;
    color: #fff;
    font-weight: bold;
    text-transform: uppercase;
    cursor: pointer;
    transition: background .3s;
}

.btn button:hover{
    background: #0c7cec;
}

.follow,
.socials{
    display: flex;
    justify-content: flex-end;
}



</style>
