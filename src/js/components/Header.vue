<template>
  <header>
        <div class="logo">
            <h1><span calss="light">Light</span> Dashboard</h1>
        </div>
        <div class="leftAlign">
            <div class="search">
                <input type="text" class="head-search" name="search" placeholder="Search" id="search">
                <button class="icon">
                    <i class="fas fa-search"></i>
                </button>
            </div>
            <ul class="icon-section">
                <li class="user">
                    <div class="circle">
                        <!-- <img /> -->
                    </div>
                    <p class="name">Lorem ispum</p>
                </li>
                <li>
                    <i class="fas fa-th"></i>
                </li>
                <li>
                    <i class="far fa-bell"></i>
                </li>

            </ul>
        </div>

    </header>

</template>
<script>
export default {
  name: 'Header',
};
</script>
<style  scoped>

header{
    width: calc(100% - 600px);
    padding: 0px 16px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    
}
.logo{
  padding: 18px 14px 18px 16px;
}
h1{
    font-size: 24px;
    word-spacing: 1px;
    font-style: italic;
}
.leftAlign{
    display: flex;
    /* width: 45%; */
    justify-content: flex-end;
    padding: 18px 14px 18px 16px;
}
.search{
    display: flex;
    margin-right:1rem!important;
}
.head-search{
    border: none;
    outline: none;
    border: 0.5px solid rgba(244,244,245,.6);
    width: 208px;
    height: 35px;
    line-height: 1.7;
    color: rgba(244,244,245,.6);  
    background-color: #21244A;
    padding: .6rem 2.85rem;
    border-radius: 5px;
}

ul {
    list-style-type: none;
}

.icon{
    position: absolute;
    height: 30px;
    outline: none;
    font-size: 1rem;
    padding: .5rem .75rem;
    border: none;
    color: rgba(244,244,245,.6);
    background-color: #21244A;
    border-radius: 5px;
    margin: 2px 0px 0px 2px;

}
.user{
    display: flex;
    align-items: center;
}
.name{
    font-size: 12px;
    font-weight: 400;
    margin: -3px 6px 0px 8px;
}
.icon-section{
    display: flex;
}
li{ 
    display: flex;
    align-items: center;
    padding: 6px 14px 9px 16px;

}
p{
    margin: 0px 10px;
    font-size: 12px;
}
.circle{
    margin: -3px 0px 0px 0px;
    height: 24px;
    width: 25px;
    background: white;
    border-radius: 20px;
}
</style>
