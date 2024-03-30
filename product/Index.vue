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
        <div class="card">
          <div class="card-body table-responsive">
            <router-link :to="{ name: 'product.create' }"><button class="btn btn-sm btn-success" type="submit">Tambah</button></router-link> 
            <table class="table ">
              <thead>
                <tr>
                  <th scope="col">#</th>
                  <th scope="col">Nama Produk</th>
                  <th scope="col">Deskripsi Produk</th>
                  <th scope="col">Harga</th>
                  <th scope="col">Jumlah</th>
                  <th scope="col">Actions</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">1</th>
                  <td>Mark</td>
                  <td>Otto</td>
                  <td>Otto</td>
                  <td>12</td>
                  <td class="d-flex gap-1"> 
                    <router-link :to="{path:'/edit/1'}"><button class="btn btn-sm btn-success" type="submit">Edit</button></router-link> 
                    <button class="btn btn-sm btn-danger" type="submit">Hapus</button>
                  </td>
                </tr> 
                <tr>
                  <th scope="row">1</th>
                  <td>Mark</td>
                  <td>Otto</td>
                  <td>Otto</td>
                  <td>12</td>
                  <td class="d-flex gap-1"> 
                    <router-link :to="{path:'/edit/1'}"><button class="btn btn-sm btn-success" type="submit">Edit</button></router-link> 
                    <button class="btn btn-sm btn-danger" type="submit">Hapus</button>
                  </td>
                </tr> 
               
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
