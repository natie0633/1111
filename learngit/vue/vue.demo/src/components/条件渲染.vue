<template>
    <h3>条件渲染</h3>
    <div v-if="flag">能看见没</div>
    <div v-if="show">能看见没</div>
</template>
<script>
// if
// export default{
//     data(){
//         return{
//             flag:true
//         }
//     }
// }


// show
export default{
    data(){
        return{
            flag:true
        }
    }
}
</script>