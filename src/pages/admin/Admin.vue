<template>

    <Nav/>

    <div class="container-fluid">
        <div class="row">

            <Menu/>

            <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4">

                <router-view/>
            </main>
        </div>
    </div>
</template>

<script>

import Nav from '@/components/Nav.vue';
import Menu from '@/components/Menu.vue';

export default {
  name: 'Admin',
  components: {
    Menu,
    Nav,
  },
};
</script>
