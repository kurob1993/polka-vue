<template>
  <div>
    <div class="row page-titles">
      <div class="col-md-5 align-self-center">
        <h4 class="text-themecolor">Starter Page</h4>
      </div>
      <div class="col-md-7 align-self-center text-right">
        <div class="d-flex justify-content-end align-items-center">
          <ol class="breadcrumb">
            <li class="breadcrumb-item">
              <a href="javascript:void(0)">Home</a>
            </li>
            <li class="breadcrumb-item active">Starter Page</li>
          </ol>
          <button type="button" class="btn btn-info d-none d-lg-block m-l-15">
            <i class="fa fa-plus-circle"></i> Create New
          </button>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-12">
        <div class="card">
          <div class="card-body">This is some text within a card block.</div>
        </div>
      </div>
    </div>
  </div>
  
</template>

<script>
export default {
  name: "StarterKit"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
