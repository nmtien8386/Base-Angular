//Add-Update Form
<form class="w-full">
    <div class="mb-3">
      <label for="name" class="form-label">Name</label><br>
      <input type="text" class="border-solid border-2 border-red-700" id="name" 
      placeholder="name" name="name"/>
    </div>
    <div class="mb-3">
      <label for="price" class="form-label">Price</label><br>
      <input type="number" class="border-solid border-2 border-red-700"id="price" 
      placeholder="price" name="price"/>
    </div>
    <div class="mb-3">
      <label for="quality" class="form-label">Quality</label><br>
      <input type="number" class="border-solid border-2 border-red-700"id="quality" 
      placeholder="quality" name="quality"/>
    </div>
    <div class="mb-3">
      <label for="description" class="form-label">Description</label><br>
      <input type="text" class="border-solid border-2 border-red-700" id="description" placeholder="description" name="description"/>
    </div>
    <div class="mb-3">
      <label for="image" class="form-label">Image</label><br>
      <input type="text" class="border-solid border-2 border-red-700" id="image"
      placeholder="image" name="image"/>
    </div>
    <button type="submit" class="w-32 h-10 bg-blue-500 rounded-lg">Submit</button>
  </form>

  ///List
  <div class="overflow-x-auto">
    <table class="min-w-full divide-y-2 divide-gray-200 text-sm text-center">
      <thead class="ltr:text-left rtl:text-right bg-blue-300">
        <tr>
          <th></th>
          <th class="whitespace-nowrap px-4 py-2 font-medium text-gray-900">Name</th>
          <th class="whitespace-nowrap px-4 py-2 font-medium text-gray-900">Price</th>
          <th class="whitespace-nowrap px-4 py-2 font-medium text-gray-900">Quality</th>
          <th class="whitespace-nowrap px-4 py-2 font-medium text-gray-900">Description</th>
          <th class="whitespace-nowrap px-4 py-2 font-medium text-gray-900">Image</th>
          <th><a routerLink="">Add</a></th>
          <th></th>
        </tr>
      </thead>
      <tbody class="min-w-full text-sm">
        <tr>
          <td></td>
          <td class="whitespace-nowrap px-4 py-2 font-medium text-gray-900"></td>
          <td class="whitespace-nowrap px-4 py-2 text-gray-700"></td>
          <td class="whitespace-nowrap px-4 py-2 text-gray-700"></td>
          <td class="whitespace-nowrap px-4 py-2 text-gray-700"></td>
          <td class="whitespace-nowrap px-4 py-2 text-gray-700">
            <img src="" alt="">
          </td>
          <td><button type="submit">Delete</button></td>
          <td><a [routerLink]="">Update</a></td>
        </tr>
      </tbody>
    </table>
</div>
