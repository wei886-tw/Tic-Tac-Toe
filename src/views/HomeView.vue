<template>
  <div class="container-fluid px-0">
    <div class="container">
      <h1 class="fs-64 text-center pt-60 mb-32">Tic Tac Toe</h1>
      <table class="mx-auto table-responsive" style="max-width: 100%">
        <thead>
          <tr>
            <th scope="col"></th>
            <th scope="col"></th>
            <th scope="col"></th>
          </tr>
        </thead>
        <tr>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
        </tr>
      </table>
    </div>
  </div>
</template>

<style>
@media (max-width: 576px) {
  td {
    border: 2px solid;
    width: 100px;
    height: 100px;
  }
}
@media (min-width: 577px) {
  td {
    border: 2px solid;
    width: 150px;
    height: 100px;
  }
}
@media (min-width: 768px) {
  td {
    border: 2px solid;
    width: 200px;
    height: 150px;
  }
}
</style>