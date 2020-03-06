<template>
    <div>
    <b-navbar toggleable="lg" type="dark" variant="dark" fixed="top">
        <b-navbar-brand href="#">Xfero</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
            <b-nav-form>
            <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
            </b-nav-form>

            <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
            </b-nav-item-dropdown>

            <b-nav-item>Documentations</b-nav-item>
            <b-nav-item>Guides</b-nav-item>
            <b-nav-item>Contributes</b-nav-item>
            <b-button size="sm" class="my-4 my-sm-2" variant="danger" to="/login">Sign Up</b-button>
        </b-navbar-nav>
        </b-collapse>
    </b-navbar>
    </div>
</template>

<style scoped>
</style>