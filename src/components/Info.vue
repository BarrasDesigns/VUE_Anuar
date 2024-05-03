<template>
    <div class="component">
        <div class="container">

            <div class="container__item">
                <h3>Alergias</h3>
                <ul>
                    <li>Mariscos</li>
                    <li>Gluten</li>
                    <li>Lactosa</li>
                    <li>Kiwi</li>
                    <li>Chocolate</li>
                </ul>
            </div>
            <div class="container__item">
                <h3>Medicamentos</h3>
                <ul>
                    <li>Nootropil</li>
                    <li>Risperidona</li>
                </ul>
            </div>
            <div class="container__item">
                <h3>Me tranquilizo con:</h3>
                <ul>
                    <li>Burbujas</li>
                    <li>Carritos</li>
                    <li>Letras y Números</li>
                    <li>Gelatinas</li>
                    <li>Manzanas</li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style>
.container {
    width: 80%;
    margin: 0 auto;
    display: grid;
    grid-template-rows: auto;
    grid-template-areas: "A M I";
    background-color: blue;
    border-radius: 20%;
}

.container__item {
    display: flex;
    flex-direction: column;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: auto;
    text-align: center;
    color: var(--fuentes);
}

.container__item:nth-child(1) {
    grid-area: A;

}

.container__item:nth-child(2) {
    grid-area: M;
}

.container__item:nth-child(3) {
    grid-area: I;
}

.container__item>ul {
    display: flex;
    flex-direction: column;
    text-align: center;
}

@media (max-width: 760px) {
    .container {
        grid-template-areas: "A"
            "M"
            "I";

    }
}
</style>