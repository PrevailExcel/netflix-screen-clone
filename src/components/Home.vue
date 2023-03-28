<script setup>
import Nav from './Nav.vue';
import Head from './Head.vue';
let user = 'Prevail'
</script>

<template>
    <Head />

    <main class="container px-3">
        <div class="mx-auto mt-5 center text-center">

            <div class="d-flex justify-content-between pt-3 mx-4">
                <span>TV Shows</span>
                <span>Movies</span>
                <span>Categories <i class="fa fa-caret-down"> </i></span>
            </div>
            <img src="/net-3.jpg" class="img-fluid mt-5 mb-4" height="360" width="200">

            <div class="d-flex justify-content-between clist mx-3">
                <span>Inspiring</span>
                <span>Drama</span>
                <span>Emotional</span>
                <span>Heartfelt</span>
                <span>Dysfunctional Family</span>
            </div>

            <div class="d-flex justify-content-around my-3">
                <i class="fa fa-plus"> <br> <small>My List</small></i>

                <div class="px-4 py-2 bg-light rounded play-btn">
                    <i class="fa fa-play"> </i> Play
                </div>

                <div>
                    <i class="rounded fa fa-info-circle">
                        <br><small>Info</small>
                    </i>
                </div>
            </div>
        </div>
    </main>

    <h5 class="ps-2 fw-bold">Continue Watching for {{user}}</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-3">
        <template v-for="i in 5">
            <div class="sitem">
                <div class="card rounded">
                    <div class="position-relative">
                        <img src="/net-1.jpg" class="card-img-top" height="150" width="100">
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <i class="ps-4 fa fa-play fa-2x mplay-btn"> </i>
                        </div>
                        <div class="position-absolute bottom-0 start-50 translate-middle-x show-title-overlay">
                            <small>2h 43m</small>
                        </div>
                    </div>
                    <span class="border-bottom border-light position-relative" style="width: 100%;">
                        <span class="border-bottom border-danger position-absolute start-0" style="width: 60%;"></span>
                    </span>

                    <div class="py-2 px-4">
                        <div class="d-flex justify-content-between">
                            <i class="fa fa-info border rounded-circle px-2 py-1"> </i>
                            <i class="fa fa-ellipsis-v p-1"> </i>
                        </div>
                    </div>
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <div class="position-relative">
                        <img src="/net-2.jpg" class="card-img-top" height="150" width="100">
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <i class="ps-4 fa fa-play fa-2x mplay-btn"> </i>
                        </div>
                        <div class="position-absolute bottom-0 start-50 translate-middle-x show-title-overlay">
                            <small>S1:E10</small>
                        </div>
                    </div>
                    <span class="border-bottom border-light position-relative" style="width: 100%;">
                        <span class="border-bottom border-danger position-absolute start-0" style="width: 90%;"></span>
                    </span>
                    <div class="py-2 px-4">
                        <div class="d-flex justify-content-between">
                            <i class="fa fa-info border rounded-circle px-2 py-1"> </i>
                            <i class="fa fa-ellipsis-v p-1"> </i>
                        </div>
                    </div>
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <div class="position-relative">
                        <img src="/net-4.jpg" class="card-img-top" height="150" width="100">
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <i class="ps-4 fa fa-play fa-2x mplay-btn"> </i>
                        </div>
                        <div class="position-absolute bottom-0 start-50 translate-middle-x show-title-overlay">
                            <small>S4:E16</small>
                        </div>
                    </div>
                    <span class="border-bottom border-light position-relative" style="width: 100%;">
                        <span class="border-bottom border-danger position-absolute start-0" style="width: 10%;"></span>
                    </span>
                    <div class="py-2 px-3">
                        <div class="d-flex justify-content-between">
                            <i class="fa fa-info border rounded-circle px-2 py-1"> </i>
                            <i class="fa fa-ellipsis-v p-1"> </i>
                        </div>
                    </div>
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <div class="position-relative">
                        <img src="/net-5.jpg" class="card-img-top" height="150" width="100">
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <i class="ps-4 fa fa-play fa-2x mplay-btn"> </i>
                        </div>
                        <div class="position-absolute bottom-0 start-50 translate-middle-x show-title-overlay">
                            <small>1h 58m</small>
                        </div>
                    </div>
                    <span class="border-bottom border-light position-relative" style="width: 100%;">
                        <span class="border-bottom border-danger position-absolute start-0" style="width: 35%;"></span>
                    </span>
                    <div class="py-2 px-4">
                        <div class="d-flex justify-content-between">
                            <i class="fa fa-info border rounded-circle px-2 py-1"> </i>
                            <i class="fa fa-ellipsis-v p-1"> </i>
                        </div>
                    </div>
                </div>
            </div>
        </template>
    </div>

    <h5 class="ps-2 pt-3 fw-bold">Exciting US TV Action & Adventure</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-3">
        <template v-for="i in 3">
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-5.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-3.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-1.jpg" class="card-img-top" height="150" width="100">

                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-1.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
        </template>
    </div>

    <h5 class="ps-2 fw-bold">Trending</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-5">
        <template v-for="i in 4">
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-7.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-8.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-6.jpg" class="card-img-top" height="150" width="100">

                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-1.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
        </template>
    </div>

    <h5 class="ps-2 fw-bold">Mobile Games</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-5">
        <template v-for="i in 4">
            <div class="sitem">
                <div class="card rounded">
                    <img src="/game-1.jpg" class="card-img-top game" height="100" width="100">
                </div>
                <div class="py-1 gtitle mb-3">
                    <h6>SpongeBob: Get Cooking</h6>
                    <small>Adventure</small>
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/game-2.png" class="card-img-top game" height="100" width="100">
                </div>
                <div class="py-1 gtitle mb-3">
                    <h6>Country Friends</h6>
                    <small>Simulation</small>
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/game-3.webp" class="card-img-top game" height="100" width="100">
                </div>
                <div class="py-1 gtitle mb-3">
                    <h6>Tomb Raider Reloaded</h6>
                    <small>Action</small>
                </div>
            </div>
        </template>
    </div>

    <h5 class="ps-2 fw-bold">Award-Winning TV Shows</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-5">
        <template v-for="i in 4">
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-4.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-2.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-5.jpg" class="card-img-top" height="150" width="100">

                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-7.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
        </template>
    </div>

    <h5 class="ps-2 fw-bold">Criminal Investigation TV Dramas</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-5">
        <template v-for="i in 4">
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-6.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-3.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-5.jpg" class="card-img-top" height="150" width="100">

                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-7.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
        </template>
    </div>

    <h5 class="ps-2 fw-bold">Kid's TV</h5>
    <div class="ps-2 scrolltab flex-row flex-nowrap mb-5">
        <template v-for="i in 4">
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-8.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-1.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-3.jpg" class="card-img-top" height="150" width="100">

                </div>
            </div>
            <div class="sitem">
                <div class="card rounded">
                    <img src="/net-2.jpg" class="card-img-top" height="150" width="100">
                </div>
            </div>
        </template>
    </div>

    <div class="p-5"></div>
    <Nav />
</template>

<style>
.clist {
    font-size: 10px;
    color: white;
}

.border {
    color: rgb(223, 223, 223) !important;
}

.play-btn {
    color: black;
}

.mplay-btn {
    border-radius: 50%;
    border: 2px solid white;
    text-align: center;
    padding: 15px;
    background-color: rgba(0, 0, 0, 0.5);
}

div.scrolltab {
    overflow-x: auto !important;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
}

.sitem {
    display: inline-block !important;
    text-align: center;
    margin-right: 7px;
    min-width: 30%;
    max-width: 31%;
}

.show-title-overlay {
    background-color: rgba(0, 0, 0, 0.833);
}
.gtitle{
    text-align: left !important; 
    line-height: 1px !important;
}
.gtitle small {
    font-size: 13px;
    color: rgb(129, 129, 129) !important;
}
.game {
    border-radius: 15% !important;
}
</style>