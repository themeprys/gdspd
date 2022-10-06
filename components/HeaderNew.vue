<template>
<div class="gd_navbarwrapper">
    <b-navbar class="gd_navbar container gd_navbarlinks">

        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="~/static/img/logo.webp"
                    alt="Godspeed Kreativa"
                    width="270px"
                >
            </b-navbar-item>
        </template>
        <!-- <template #start>
            <b-navbar-item href="#">
                Home
            </b-navbar-item>
            <b-navbar-item href="#">
                Documentation
            </b-navbar-item>
            <b-navbar-dropdown label="Info">
                <b-navbar-item href="#">
                    About
                </b-navbar-item>
                <b-navbar-item href="#">
                    Contact
                </b-navbar-item>
            </b-navbar-dropdown>
        </template> -->

        <template #end>
            <b-navbar-item tag="router-link" to="/">Home</b-navbar-item>          
            <b-navbar-item tag="router-link" to="/about-us">About Us</b-navbar-item>          
            <b-navbar-item tag="router-link" to="/our-clients">Our Clients</b-navbar-item>          
            <b-navbar-item tag="router-link" to="/our-services">Our Services</b-navbar-item>        
        </template>

    </b-navbar>
</div>
</template>