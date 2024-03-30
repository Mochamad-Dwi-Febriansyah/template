<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container">
      <a class="navbar-brand" href="#">Dashboard Product</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0"></ul>
        <div class="d-flex gap-3 align-items-center">
          <span class="">Mochamad Dwi Febriansyah</span>
          <button class="btn btn-danger" type="submit">Logout</button>
        </div>
      </div>
    </div>
  </nav>

  <div class="container my-5">
    <div class="row">
      <div class="col-md-12">
          <router-link :to="{ name: 'product.index' }"><button class="btn btn-sm btn-danger mb-2" type="submit">< kembali</button></router-link>
        <div class="card">
          <div class="card-body">
            <h2 class="mb-2">Edit Product</h2>
            <form>
                <div class="mb-3">
                <label class="form-label">Nama Produk</label>
                <input type="text" class="form-control"/> 
              </div>
              <div class="mb-3">
                  <label class="form-label">Deskripsi</label>
                  <textarea name="" id="" cols="30" rows="3" class="form-control"></textarea> 
                </div> 
                <div class="mb-3">
                <label class="form-label">Harga Produk</label>
                <input type="number" class="form-control"/> 
              </div>
                <div class="mb-3">
                <label class="form-label">Jumlah Produk</label>
                <input type="number" class="form-control"/> 
              </div>
                <div class="mb-3">
                <label class="form-label">Kategori Produk</label>
                <select name="" id=""  class="form-control">
                    <option value="pakaian">Elektronik</option>
                    <option value="pakaian">Pakaian</option>
                    <option value="pakaian">Konsumsi</option>
                </select>
              </div>
                <div class="mb-3">
                <label class="form-label">Status Produk</label>
                <select name="" id=""  class="form-control">
                    <option value="active">Active</option>
                    <option value="inactive">In Active</option> 
                </select>
              </div>
              <button type="submit" class="btn btn-primary">Kirim</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
