<template>
    <div class="tabs-header-container-group bg-gray-100">

        <div class="tab content w-full overflow-auto text-sm font-medium flex algin-center justify-start">
            <div class="border w-auto py-1 px-2">
            <small class="text-sm  mr-2"><i class="fas fa-plus-circle"></i></small>
            <small>Libary One</small>
            </div>

            <div class="border w-auto py-1 px-2 ">
            <small>Draft Two</small>
            <small class="text-sm  ml-2"><i class="fas fa-times"></i></small>
            </div>

             <div class="border w-auto py-1 px-2 ">
            <small>Section Three</small>
            <small class="text-sm  ml-2"><i class="fas fa-times"></i></small>
            </div>

             <div class="border w-auto py-1 px-2 ">
            <small>Explore five</small>
            <small class="text-sm  ml-2"><i class="fas fa-times"></i></small>
            </div>
            <div>

            </div>
        </div>
       
    </div>    
</template>

<script lang="ts">
import {Vue} from 'vue-class-component'
export default class Tabs extends Vue{
    
}
</script>