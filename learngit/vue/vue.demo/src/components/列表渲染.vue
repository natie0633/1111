<!-- <template>
   <div>
    <p v-for="item in names">{{ item }}</p>
   </div>
</template>
<script>
export default{
    data(){
        return{
            names:["sss","sssddw"]
        }
    }
}
</script> -->

<template>
    <div v-for="item in result">
   <p>{{ item.title }}</p>
   <img :src="item.avator" alt="">
    </div>
 </template>
 <script>
 export default{
     data(){
         return{
            result:[{
                "id":123456,
                "name":"sssss",
                "title":"打撒哒哒哒哒哒哒"
            },
            {
                "id":12345678,
                "name":"ssssssds",
                "title":"打撒哒哒dasdada哒哒哒哒"
            },
        ]
         }
     }
 }
 </script>
 <script>
    export default {
        data(){
            return{
                names:["sss","sssddw"]
            }
        }
}
</script>
 