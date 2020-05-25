<template>
  <div>
    <AdminHeader />
    <div class="container-fluid">
      <div class="row">
        <AdminSidebar />
        <main role="main" class="col-md-9 ml-sm-auto col-lg-10 px-md-4">
          <nuxt />
        </main>
      </div>
    </div>
  </div>
</template>

<script>
import AdminSidebar from '@/components/AdminSidebar'
import AdminHeader from '@/components/AdminHeader'

export default {
  components: {
    AdminHeader,
    AdminSidebar
  }
}
</script>

<style>
body {
  font-size: 0.875rem;
}
</style>
