<template>
     <div class="wrapper">
                <h2>lorem ispum</h2>
                <div class="row alignItems">
                    <div class="banner">
                    </div>
                    <div class="infocard">

                    </div>
                </div>
                <div class="row">
                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>
                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>
                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>
                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>
                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>

                    <div class="card">
                        <figure>
                        </figure>
                        <div class="info">
                        </div>
                    </div>
                </div>
            </div>
</template>
<script scoped>
export default {
  name: 'Container',
};
</script>
<style scoped>
.wrapper{
    margin: 10px 0px;
    height: 100vh;
    width: calc(100% - 300px);

}
.wrapper h2{
    margin-bottom: 20px;
    font-size: 35px;
    font-weight: 300;
}

.row{
    display: flex;
    flex-wrap: wrap;
}
.card{
    flex: 1 1 15%;
    min-width: 150px;
    background-color: #10101b;
    height: 150px;
    margin: 5px;
    max-width: 19%;
    border-radius: 5px;
}

.alignItems{
    display: flex;
    justify-content: space-between;
}

</style>