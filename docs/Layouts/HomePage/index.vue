<template lang="html">
  <div>
    <sui-menu fixed>
      <sui-container>
        <sui-menu-item active>Home</sui-menu-item>
        <sui-menu-item>Work</sui-menu-item>
        <sui-menu-item>Company</sui-menu-item>
        <sui-menu-item>Careers</sui-menu-item>
        <sui-menu-menu position="right">
          <sui-menu-item>
            <sui-button>Login</sui-button>
          </sui-menu-item>
          <sui-menu-item>
            <sui-button class-name="primary">
              Sign Up
            </sui-button>
          </sui-menu-item>
        </sui-menu-menu>
      </sui-container>
    </sui-menu>
  </div>
</template>

<script>
export default {};
</script>
