<template>
                <div class="rightNav">
                <h4 class="navHead">
                    Multiple selection
                </h4>
                <img class="nav_img" src="../../assets/img.jpg" />
                <ul class="sideNav">
                   
                    <li><i class="fas fa-caret-right"></i>
                        <p> paragraph describing Mars or a one-topic paragraph describing</p>
                    </li>
                    <li><i class="fas fa-caret-right"></i>
                        <p>one-topic paragraph</p>
                    </li>
                    <li><i class="fas fa-caret-right"></i>
                        <p>paragraph describing</p>
                    </li>
                    <li><i class="fas fa-caret-right"></i>
                        <p>Chinses</p>
                    </li>
                    <li><i class="fas fa-caret-right"></i>
                        <p>Others</p>
                    </li>
                </ul>
                <div class="details">
                    <input class="detail" type="text" name="text" id="text">
                    <i class="fas fa-times"></i>
                </div>
                <div class="details">
                    <input class="detail" type="text" name="text" id="text">
                    <i class="fas fa-times"></i>
                </div>
                <div class="tags">
                    <p>Lorem ispim</p>
                    <p>Lorem ispim</p>
                    <p>Lorem ispim</p>
                    <p>Lorem ispim</p>
                    <p>Lorem ispim</p>
                    <p>Lorem ispim</p>
                </div>
            </div>
</template>
<script scoped>
export default {
  name: 'RightNav',
};
</script>
<style scoped>
.rightNav{
    position: fixed;
    width: 300px;
    height: 100vh;
    background-color: #10101b;
    border-radius: 5px;
    margin:0px 0px 15px 5px ;
    right: 0;
    display: flex;
    flex-direction: column;
    top:0;
}
.navHead{
padding: 10px 30px;
border-radius: 10px;
background-color: #1E2146;
text-align: center;
}
.nav_img{
    margin: 0px 10px;
    border-radius: 10px;
    width: 280px;
    height: 200px;
}
.details{
    display: flex;
    align-items: center;

}
.detail{
    width: 240px;
    height: 35px;
    margin: 0px 10px 3px 15px;
}
.tags{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 10px 0px;
}
.tags p{
    width: 40%;
    background-color: #1E2146;
    margin: 5px;
    border-radius: 8px;
    padding: 10px 20px;
}
</style>