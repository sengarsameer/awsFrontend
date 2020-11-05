<template>
    <div class="homepage">
        <nav-bar />
        <div class="content">
            <side-bar />
            <dash-board />
        </div>
    </div>
</template>

<script>
import NavBar from "./components/NavBar";
import SideBar from "./components/SideBar";
import DashBoard from "./components/DashBoard";

export default {
    name: "HomePage",
    components: {
        NavBar,
        SideBar,
        DashBoard,
    },
    data() {
        return {};
    },
};
</script>

<style>
    .content {
        margin-top: 50px;
    }
</style>
