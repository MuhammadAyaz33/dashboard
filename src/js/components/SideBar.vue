<template>
      <div class="navigationBar">
                <div class="section">
                    <div class="head">
                        <div class="home">
                            <i class="fas fa-home"></i>
                        </div>
                        <p>Dashboard</p>
                    </div>
                    <ul class="sideNav">
                        <li>
                            <i class="fas fa-caret-down"></i>
                            <p> Galleries </p>
                        </li>
                        <li class="dropli"><i class="fas fa-grip-horizontal"></i>
                            <p>Sandiago 2019</p>
                        </li>
                        <li><i class="fas fa-caret-right"></i>
                            <p>World</p>
                        </li>
                        <li><i class="fas fa-caret-right"></i>
                            <p>Continentel</p>
                        </li>
                        <li><i class="fas fa-caret-right"></i>
                            <p>Italian</p>
                        </li>
                        <li><i class="fas fa-caret-right"></i>
                            <p>Chinses</p>
                        </li>
                        <li><i class="fas fa-caret-right"></i>
                            <p>Others</p>
                        </li>
                    </ul>
                    <p class="navhead">LABELS</p>
                    <ul class="timeline">

                        <li>Galleries</li>
                        <li>World</li>
                        <li>Continentel</li>
                        <li>Italian</li>
                    </ul>
                </div>
                <!-- <div class="fixed">
                <div class="profile">
                    <div class="user">
                        <div class="circle">
                        </div>
                        <p>name</p>
                    </div>
                    <div class="question"></div>
                </div>
            </div> -->
            </div>
</template>
<script scoped>
export default {
  name: 'SideBar',
};
</script>
<style>
.navigationBar{
    width: 300px;
    height: 100vh;
    padding: 16px 0px 0px 16px;
    position: fixed;
    top: 0px;
    border-radius: 6px;
    background: #09091a;
    left:0;
}
.head{
    display: flex;
    align-items: center;
    color: rgba(244,244,245,.9);

}
.head p {
    margin: 0px 5px;
    font-weight: 600;
}
.dropli{
padding-left: 40px;
background-color: #27212e;
border-right: 5px solid aliceblue;
}

.home{
    padding: 0px 18px;
}
.sideNav{
    margin: 15px 0px 0px 25px; 
    padding: 10px 0px;
}
.navhead{
    font-weight: 600;
    margin: 10px;
    font-style: italic;
}
.timeline li{
    font-size: 14px;
padding: 10px 0px 0px 30px;
}
.flex{
    display: flex;
    justify-content: end;
    position: relative;
}

</style>