<template>
  <div class="container mt-5 d-flex justify-content-center">
    <div class="row">
      <div class="col-md-12">
        <h1 class="text-center mb-3">Silahkan Register</h1>
        <div class="card" style="width: 27rem">
          <div class="card-body">
            <form>
              <div class="mb-3">
                <label class="form-label">Name</label>
                <input type="text" class="form-control"/> 
              </div>
              <div class="mb-3">
                <label class="form-label">Username</label>
                <input type="text" class="form-control"/> 
              </div>
              <div class="mb-3">
                <label class="form-label">Password</label>
                <input type="password" class="form-control"/>
              </div> 
              <div class="mb-3">
                <label class="form-label">Jenis Kelamin</label>
                <select name="" id="" class="form-control">
                  <option value="pria">Pria</option>
                  <option value="wanita">Wanita</option>
                </select>
              </div> 
              <div class="mb-3">
                <label class="form-label">Alamat</label> 
                <textarea name="" class="form-control" id="" cols="30" rows="3"></textarea>
              </div> 
              <router-link :to="{ name: 'login' }" class="d-block mb-1">login</router-link>
              <button type="submit" class="btn btn-primary">Register</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
