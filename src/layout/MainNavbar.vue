<template>
    <navbar position="fixed"
            type="primary"
            :transparent="transparent"
            :color-on-scroll="colorOnScroll"
            menu-classes="ml-auto">
        <template slot="navbar-menu">
            <li class="nav-item">
                <a class="nav-link" rel="tooltip" title="Check out my Github" data-placement="bottom" href="https://github.com/adambeck7" target="_blank">
                    <i class="fab fa-github-square fa-2x"></i>
                    <p class="d-lg-none d-xl-none">Github</p>
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" rel="tooltip" title="View my LinkedIn" data-placement="bottom" href="https://www.linkedin.com/in/adam-beck-5b191212/" target="_blank">
                    <i class="fab fa-linkedin"></i>
                    <p class="d-lg-none d-xl-none">LinkedIn</p>
                </a>
            </li>

        </template>
    </navbar>
</template>

<script>
import { DropDown, NavbarToggleButton, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    DropDown,
    Navbar,
    NavbarToggleButton,
    NavLink,
    [Popover.name]: Popover
  }
};
</script>

<style scoped>
</style>
