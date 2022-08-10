<template>
<section>
 <div class="container flex p-20 justify-center" id="education">

<div>
   <h4 class="p-20"> Academic Qualification </h4><br>
    
</div>
<div class="overflow-x-auto relative shadow-md sm:rounded-lg p-20">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="py-3 px-6">
                    Exam Title
                </th>
                <th scope="col" class="py-3 px-6">
                    Concentration/Major
                </th>
                <th scope="col" class="py-3 px-6">
                    Institute
                </th>
                <th scope="col" class="py-3 px-6">
                    Result
                </th>
                <th scope="col" class="py-3 px-6">
                    Pas. Year
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    BSC
                </th>
                <td class="py-4 px-6">
                   Computer Science and Engineering
                </td>
                <td class="py-4 px-6">
                    North South University
                </td>
                <td class="py-4 px-6">
                    2.82/4
                </td>
                <td class="py-4 px-6">
                    2022
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    HSC
                </th>
                <td class="py-4 px-6">
                    Science
                </td>
                <td class="py-4 px-6">
                    Milestone College
                </td>
                <td class="py-4 px-6">
                    4.93/5
                </td>
                <td class="py-4 px-6">
                    2017
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    SSC
                </th>
                <td class="py-4 px-6">
                    Science
                </td>
                <td class="py-4 px-6">
                    Rajdhani High School
                </td>
                <td class="py-4 px-6">
                    4.56/5
                </td>
                <td class="py-4 px-6">
                    2015
                </td>
            </tr>
        </tbody>
    </table>
</div>


  

  

 </div>
 </section>
</template>
 

<script>
export default {
  name: 'education',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.container {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}

</style>
