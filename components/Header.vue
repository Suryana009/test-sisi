<!-- Please remove this file from your project -->
<template>
    <div>
        <b-navbar toggleable="lg" type="light" variant="default" >
            <b-navbar-brand href="#">
                <img src="~/assets/logo-at.png" style="width: 110px; height: 40px;" />
            </b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item href="#">Laman Utama</b-nav-item>
                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                    <b-nav-form>
                    <b-form-input size="sm" class="mr-sm-2" placeholder="Cari Produk .."></b-form-input>
                    <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                    </b-nav-form>

                    <b-navbar-nav right>
                        <b-nav-item href="#">Cart</b-nav-item>
                        <b-nav-item href="#">Laman Utama</b-nav-item>
                    </b-navbar-nav>
                
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>
