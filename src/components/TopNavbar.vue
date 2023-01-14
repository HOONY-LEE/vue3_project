<template>
    <div class="top_navbar_container out1">
        <div class="nav_item_box left_box out1">왼쪽 박스</div>
        <div class="nav_item_box right_box out1">오른쪽 박스</div>
    </div>
</template>

<script>
export default {
    name: 'TopNavbar',
    props: {

    }
}
</script>

<style scoped>
    .top_navbar_container {
        width: 100%;
        height: 50px;
        background-color: gray;
        position: fixed;
        display: flex;
        justify-content: space-between;
    }
    .nav_item_box {
        width: 100px;
        height: 40px;
        background-color: white;
        display: flex;
        margin-top: 4px;
    }
    .top_navbar_container .right_box {
        width: 30%;
    }
    .top_navbar_container .left_box {
        width: 10%;
    }
</style>

