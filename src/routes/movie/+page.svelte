<style>
    :root {
    --primary-color: rgb(10, 7, 4);
    --secodary-color: rgb(70, 47, 18);
}

* {
    box-sizing:  border-box;
}

main {
    display: flex;
    flex-wrap: wrap;
}

body{
    background-color:  var(--primary-color);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
}

header {
    padding: 10px;
    display: flex;
    justify-content: flex-end;
    background-color: var(--secodary-color);
}

.search {
    background-color: transparent;
    border: 2px solid var(--primary-color);
    border-radius: 50px;
    font-family: inherit;
    font-size: 14px;
    padding: 20px 10px;
}

.search::placeholder {
    color: rgb(240, 190, 97);
}

.search.search:focus{
    outline: none;
    background-color: rgb(238, 159, 159);
}

.movie {
    width: 400px;
    margin: 20px;
    background-color: var(--secodary-color);
    box-shadow: 0 4px 7px rgba(189, 75, 75, 0.315);
    position: relative;
    overflow: hidden;
    border-radius: 3px;
}

.movie img{
    width: 100%;
}

.movie-info {
    color: rgb(194, 194, 194);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 45px 30px 30px;
    letter-spacing: 0.5px;
}

.movie-info h3{
    margin-top: 0;
}

.movie-info span{
    background-color: var(--primary-color);
    padding: 25px 5px;
    border-radius: 3px;
    font-weight: bold;
}

.movie-info span.green{
    color: rgb(211, 42, 0);
}

.overview {
    background-color: white;
    padding: 20px;
    position: absolute;
    left: 0;
    bottom: 0;
    right: 0;
    max-width: 100%;
    transform: translateY(101%);
    transition: transform 0.3s ease-in;
}

.movie:hover .overview{
    transform: translateY(0)
}
</style>

<main id="main">
    <div class="movie" id="movie">
        <div class="movie-info" id="MovieInfoDiv">
            <h3 id="MovieTitle">Твоё имя</h3>
            <span class="green">9.7</span>
        </div>
        <div class="overview">
            <h3 id="Description">История о парне из Токио и девушке из провинции, которое обнаруживают, что между ними существует странная и необъяснимая связь. 3 июля 2016 года</h3>
        </div>
    </div>
    <div class="movie" id="movie">
        <div class="movie-info" id="MovieInfoDiv">
            <h3 id="MovieTitle">Летний призрак</h3>
            <span class="green">7.0</span>
        </div>
        <div class="overview">
            <h3 id="Description">Японский короткометражный анимационный фильм, 12 ноября 2021 года</h3>
        </div>
    </div>
    <div class="movie" id="movie">
        <div class="movie-info" id="MovieInfoDiv">
            <h3 id="MovieTitle">Она видела небо</h3>
            <span class="green">9.5</span>
        </div>
        <div class="overview">
            <h3 id="Description">Родители Аой и Аканэ погибли 13 лет назад. Чтобы Заботится о младшей сестре, Акане отказалась от своей мечты переехать в Токио вместе с парнем Синносукэ.</h3>
        </div>
    </div>
    <div class="movie" id="movie">
        <div class="movie-info" id="MovieInfoDiv">
            <h3 id="MovieTitle">Её заветное желание</h3>
            <span class="green">8.2</span>
        </div>
        <div class="overview">
            <h3 id="Description">Жозе взяла себе имя героини романа Франсуазы Саган. Девушка прикована к инвалидному креслу и почти всё время проводит за читением и рисованием.</h3>
        </div>
    </div>
    <div class="movie" id="movie">
        <div class="movie-info" id="MovieInfoDiv">
            <h3 id="MovieTitle">На твоей волне</h3>
            <span class="green">7,8</span>
        </div>
        <div class="overview">
            <h3 id="Description">Первокурсница Хинако переезжает в небольшой прибрежный городок, где провела детство, и знакомится с пожарным Минато, когда тот вывозит её с крыши во время пожара.</h3>
        </div>
    </div>
    <div class="movie" id="movie">
        <div class="movie-info" id="MovieInfoDiv">
            <h3 id="MovieTitle">Дитя Погоды</h3>
            <span class="green">9.7</span>
        </div>
        <div class="overview">
            <h3 id="Description">Старшеклассник Ходака Морисима переезжает со своего родного острова в Токио, где у парня сразу кончаются деньги.</h3>
        </div>
    </div>

</main>