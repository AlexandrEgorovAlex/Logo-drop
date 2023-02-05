# Logo-drop
logo animation
.logo {
    background: #fff;
    padding: 8px 50px;
    text-transform: uppercase;                              
    font-weight: 900;
    font-size: 25px;
    transform-origin: center; /* transform element to point*/
    animation: drop 10s ease-in-out;
    transform-origin: center;

}

@keyframes drop {
    50%, 0% {
        transform: rotate(360deg);
    }
    50%, 50% {
        transform: rotate(20deg);
        opacity: 1;
    }
    100% {
        transform: translateY(30vh);
        opacity: 0;
    }
    
}
