<template>
  <div>
    <h3 class="title is-3 has-text-info">User Payment Confirmation</h3>
    <table class="table is-fullwidth is-hoverable">
      <thead>
        <tr>
          <th>No</th>
          <th>Name</th>
          <th>Batch</th>
          <th>Program Start date</th>
          <th>Program Finish Date</th>
          <th>Confirmation Date</th>
          <th>Confirmation</th>
          <th>Action</th>
        </tr>
      </thead>
      <tfoot>
        <tr>
          <th>No</th>
          <th>Name</th>
          <th>Batch</th>
          <th>Program Start date</th>
          <th>Program Finish Date</th>
          <th>Confirmation Date</th>
          <th>Confirmation</th>
          <th>Action</th>
        </tr>
      </tfoot>
      <tbody>
        <tr>
          <th>1</th>
          <td>Leicester City</td>
          <td>38</td>
          <td>23</td>
          <td>12</td>
          <td>3</td>
          <td><span class="tag is-warning">Not yet Confirmed</span></td>
          <td><button class="button is-link is-light is-small is-rounded">Detail</button></td>
        </tr>
        <tr>
          <th>2</th>
          <td>Leicester City</td>
          <td>38</td>
          <td>23</td>
          <td>12</td>
          <td>3</td>
          <td><span class="tag is-success">Confirmed</span></td>
          <td> <button class="button is-link is-light is-small is-rounded">Detail</button></td>
        </tr>

      </tbody>
    </table>
  </div>
</template>

<script>
  export default {
    layout: 'admin'
  }

</script>

<style>

</style>
