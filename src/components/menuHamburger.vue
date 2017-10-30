<template>
  <div class="menuHamburger">
    <input id="test" type="checkbox" />
    <label for="test">
        <svg class="burger" width="86" height="60" viewbox="0 0 150 150">
            <g stroke-width="12">   
                <line x1="6" y1="6" x2="80" y2="6"></line>
                <line x1="6" y1="28" x2="80" y2="28"></line>
                <line x1="6" y1="50" x2="80" y2="50"> </line>
            </g>
        </svg>
        <svg class="close" width="86" height="60" viewbox="0 0 150 150">
            <g stroke-width="12">   
                <line x1="42" y1="6" x2="42" y2="80"></line>
                <line x1="6" y1="42" x2="80" y2="42"></line>
            </g>
        </svg>
    </label>
    <div class="menu">
        <ul class="list-menu">
            <li class="item-menu"><a href="#" class="link-item-menu">Inicio</a> </li>
            <li class="item-menu"><a href="#" class="link-item-menu">Nosotros</a> </li>
            <li class="item-menu"><a href="#" class="link-item-menu">Portafolio</a> </li>
            <li class="item-menu"><a href="#" class="link-item-menu">Blog</a> </li>
        </ul>
        <!-- <div>Inicio</div>
        <div>Nosotros</div>
        <div>Portafolio</div>
        <div>Blog</div> -->
    </div>
  </div>
</template>

<script >
export default {

}
</script>

<style lang="scss">
label {
    position: absolute;
    z-index: 1;
}

input {
    display: none;
}

input:checked ~ label {
    right: 0;
}

// burger
////////////////////////////////////////////////
.burger {
    position: relative;
    top: 24px;
    cursor: pointer;
}

.burger g {
    stroke: #ffffff;
    transition: stroke 0.25s ease-in-out;    
}

.burger g:hover {
    stroke: darken(#ffffff, 20%);
}

input:checked ~ label .burger {
    opacity: 0;
}

// close
////////////////////////////////////////////////
.close {
    position: relative;
    top: 24px;
    cursor: pointer;
    opacity: 0;
}

.close g:hover {
    stroke: darken(#ffffff, 20%);
}

.close g {
    stroke: #ffffff;
    transition: stroke 0.25s ease-in-out;    
}

.close line {
    transform-origin: 0%;
}

.close g {
    transform: rotateZ(45deg);
    transform-origin: 50%;
}

input:checked ~ label .close {
    opacity: 1;
}

// menu
////////////////////////////////////////////////
.menu {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    position: absolute;
    opacity: 0;
    width: 100vw;
    height: 100vh;
    background-color: rgba(4, 42, 82, 0.9);
    transition: opacity 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    color: #ffffff;
    text-transform: uppercase;
    font-size: 24px;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
}

input:checked ~ .menu {
    opacity: 1;
}

.menu ul li {
    list-style: none;
    // margin-top: 50px;
    // transition: margin 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
.link-item-menu {
    color: #fff;
}

input:checked ~ .menu ul li {
    margin-top: 0px;
}

// main
////////////////////////////////////////////////
.main {
    display: flex;
    width: 100vw;
    height: 100vh;    
}

.main span {
    margin: auto;
    font-size: 40px;
    color: #ffffff;
    font-family: 'Pacifico', cursive;    
}



</style>
