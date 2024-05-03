<template>
    <div class="component">
        <div class="title">

            <h4>Contacta a mis padres a los siguientes números</h4>
        </div>

        <div>
            <ul>
                <li>
                    <div class="info">

                        <a href="https://wa.me/+528110633292">
                            <h5>Mi mamí</h5>
                            <img src="../assets/whatsapp.png" class="icon" alt="whatsappLogo">
                        </a>
                    </div>
                </li>
                <li>
                    <div class="info">

                        <a href="https://wa.me/+528115028945">
                            <h5>Mi papi</h5>
                            <img src="../assets/whatsapp.png" class="icon" alt="whatsappLogo">
                        </a>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>
<style>
.title {
    color: var(--fuentes);
    font-size: 22px;
    text-align: center;
}

ul {
    display: flex;
    justify-content: space-evenly;
}

li {
    list-style-type: none;
}


a {
    text-decoration: none;
    color: var(--fuentes);
    display: flex;
    flex-direction: column;
    width: 100%;
    align-items: center;
}

.info {
    height: 150px;
    width: 100%;
    display: flex;
    flex-direction: column;
    text-align: center;

}

.icon {
    max-width: 100px;
}

.icon:hover {
    background-color: var(--hoverEnlaces);
    border-radius: 50%;
    padding: 20px;
}

@media (max-width: 760px) {
    ul {
        flex-direction: column;
    }
}
</style>