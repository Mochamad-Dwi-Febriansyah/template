<template>
  <div class="container mt-5 d-flex justify-content-center">
    <div class="row">
      <div class="col-md-12">
        <h1 class="text-center mb-3">Silahkan Login</h1>
        <div class="card" style="width: 27rem">
          <div class="card-body">
            <form>
              <div class="mb-3">
                <label class="form-label">Username</label>
                <input type="text" class="form-control"/> 
              </div>
              <div class="mb-3">
                <label class="form-label">Password</label>
                <input type="password" class="form-control"/>
              </div> 
              <router-link :to="{ name: 'register' }" class="d-block mb-1">register</router-link> 
              <button type="submit" class="btn btn-primary">Login</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
