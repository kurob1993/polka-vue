<template>
  <div>
    <Header />
    <LeftSidebar />
    <div class="page-wrapper">
      <div class="container-fluid">
        <StarterKit />
        <RightSidebar />
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/layout/Header'
import LeftSidebar from './components/layout/LeftSidebar'
import RightSidebar from './components/layout/RightSidebar'
import StarterKit from './components/StarterKit'

export default {
  name: 'App',
  components: {
    Header,
    LeftSidebar,
    RightSidebar,
    StarterKit
  }
}
</script>
