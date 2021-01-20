body {
    font-family: 'Roboto', sans-serif;
}

.container {
    justify-content: center;
    flex-direction: column;
    align-items: center;
    display: flex;
    height: 100vh;
    width: 100vw;
}

.logo {
    animation: logoFadeIn ease 3s;
    width: 150px;
}

@keyframes logoFadeIn {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}


.title {
    animation: titleFadeIn ease 4s;
    text-align: center;
    font-weight: 300;
    max-width: 500px;
}

@keyframes titleFadeIn {
    0% {
        opacity: 0;
    }
    15% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    } 
}

