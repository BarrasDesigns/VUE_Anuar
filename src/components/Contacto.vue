<template>
    <div>
        <div class="title">

            <h4>Contacta a mis padres a los siguientes números</h4>
        </div>

        <div>
            <ul>

                <li>

                    <a href="https://wa.me/+528110633292">
                        <h5>Mi mamí</h5>
                        <img src="../assets/whatsapp.png" class="icon" alt="whatsappLogo">
                    </a>
                </li>
                <li>

                    <a href="https://wa.me/+528115028945">
                        <h5>Mi papi</h5>
                        <img src="../assets/whatsapp.png" class="icon" alt="whatsappLogo">
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>
<style>
a{
    text-decoration: none;
    color: var(--fuentes);
}
a:hover{
    color: var(--hoverFuentes);

}
li {
    list-style-type: none;
    
    display: flex;
    flex-direction: column;
    text-align: center;
    
}
li:hover{
    background-color: var(--hoverEnlaces);
    border-radius: 50%;
}
ul {
    
    display: flex;
    justify-content: center;

}

.icon {
    width: 50%;
}
</style>