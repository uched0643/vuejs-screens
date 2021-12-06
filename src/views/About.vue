<template>
  <div class="sales-receipt w-full h-screen">
    <div class=" flex justify-center align-center w-screen h-screen bg-gray-200">
      <div class="receipt-card bg-white shadow px-10 py-2">
        <div class="header pb-4 flex align-center justify-between border-b border-blue-500
        ">
          <div class="logo  flex justify-evenly align-center">
            <img src="" class="w-14 rounded-md h-14 border border-blue-500 mr-3" alt="">
            <h4 class="text-normal font-bold text-center mt-3 text-blue-600">LOGO <br> NAME </h4>
          </div>
          <div class="title-content text-right">
            <h1 class="font-bold text-right text-3xl text-blue-500 mt-5">Sales Receipt</h1>
          </div>
        </div>


          <div class="header pt-6 pb-2 flex align-center justify-between border-b border-blue-500
        ">
          <div class="logo flex justify-evenly flex-col align-center">
            
            <h4 >
              <small class="text-normal font-bold text-center text-blue-600">
                Your Company Name
              </small> 
            </h4>
               <small class="text-normal font-medium text-center text-blue-400">
              Your Company Sign Here
            </small>
          </div>

             <div class="logo pt-3 flex flex-col justify-evenly align-center">
            
            <small class="text-normal font-medium text-center text-blue-600">
              Date: <span class="text-sm text-blue-300">Date</span>
            </small>
               <small class="text-normal font-medium text-center  text-blue-600">
              Invoice #:<span class="text-sm text-blue-300">No</span>
            </small>
          </div>
          
        </div>

        <div class=" pt-6 pb-2 flex align-center justify-between border-b border-blue-500
        ">
          <div class="logo flex  align-center">
            
         
              <small class="text-normal font-bold text-center text-blue-600">
                Sold To: <span>
        
               <small class="text-normal font-medium text-center text-blue-400">
              Name
            </small> <br>
            
              <small class="text-normal ml-14 font-medium text-center text-blue-400">
              Company Name
            </small>
             <br>
            
              <small class="text-normal ml-14 font-medium text-center text-blue-400">
              Street Address
            </small>
             <br>
            
              <small class="text-normal ml-14 font-medium text-center text-blue-400">
              City Name
            </small>

                </span>
              </small> 
          </div>
          
        </div>


 <div class="my-6">
        <table class="w-full">
          <thead>
            <tr class="bg-white">
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Payment Method </small></th>
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Check Number </small></th>
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Job </small></th>
              
              
            </tr>
          </thead>
          <tbody>
            <tr class="bg-white">
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="First Name"><small>James</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small>James</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Job Title"><small>James</small> </td>
             
            </tr>
           
          </tbody>
        </table>
      </div>
        <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="my-6">
        <table class="w-full">
          <thead>
            <tr class="bg-white">
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Qty </small></th>
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Items # </small></th>
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Description </small></th>
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Unit Price </small></th>
               <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Discount</small></th>
              <th class="  bg-blue-500 text-white border border-indigo-300 font-bold text-sm"> <small>Line Total </small></th>
              
            </tr>
          </thead>
          <tbody>
            <tr class="bg-white">
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="First Name"><small>James</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small>James</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Job Title"><small>James</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Twitter"><small>James</small> </td>
               <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Job Title"><small>James</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Twitter"><small>James</small> </td>
            </tr>
           
          </tbody>
        </table>
      </div> <!-- table data -->

 <div class="my-6 flex justify-end">
        <table class="w-80 ">
         
          <tbody>
            <tr class="bg-white">
              <td class="px-2  text-right text-sm font-meduim" tableHeadData="First Name"><small>Total Discount</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small></small> </td>
             <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small></small> </td>
             
            </tr>
             <tr class="bg-white">
              <td class=" text-sm font-meduim" tableHeadData="Last Name"><small></small> </td>
              <td class="px-2 text-right text-sm font-meduim" tableHeadData="First Name"><small>sale discount</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small>#########</small> </td>
            </tr>
              <tr class="bg-white">
              <td class=" text-sm font-meduim" tableHeadData="Last Name"><small></small> </td>
              <td class="px-2 text-right text-sm font-meduim" tableHeadData="First Name"><small>subtotal</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small>#########</small> </td>
            </tr>
              <tr class="bg-white">
              <td class=" text-sm font-meduim" tableHeadData="Last Name"><small></small> </td>
              <td class="px-2 text-right text-sm font-meduim" tableHeadData="First Name"><small>Total</small> </td>
              <td class="pl-2 border border-indigo-300 text-sm font-meduim" tableHeadData="Last Name"><small>#########</small> </td>
            </tr>
            
           
          </tbody>
        </table>
      </div>

      <div class="notice w-full text-center flex flex-col justify-center">
        <small class="text-sm font-meduim">Thank You For Your Business!</small>
         <small class="text-sm font-meduim">street address zip code phone fax</small>
      </div>

      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.receipt-card{
  width:650px
}
</style>
